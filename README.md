# AS-2-21-02-22
PROGRAM 2
n=5
for i in range(n):
    for j in range(i,n):
        print('',end='')
        for j in range(i+1):
            print('*',end=' ')
        print()
        OUTPUT:
        ENTER NUMBER:5
                                     *
                                *    *
                           *    *    *
                      *    *    *    *
              *       *     *    *   *
