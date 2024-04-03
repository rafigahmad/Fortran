# Fortran
program Factorial
    implicit none
    integer :: n, factorial

    ! Ask user for input
    print *, "Enter a number to calculate its factorial:"
    read *, n

    ! Calculate factorial using a loop
    factorial = 1
    do while (n > 0)
        factorial = factorial * n
        n = n - 1
    end do

    ! Display the factorial
    print *, "Factorial:", factorial
end program Factorial
