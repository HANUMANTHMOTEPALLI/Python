def print_rangoli(size):
    al_list='-a-b-c-d-e-f-g-h-i-j-k-l-m-n-o-p-q-r-s-t-u-v-w-x-y-z'
    k=0
    for i in range(1,n+1):
        ri_list=''
        odd=list(range(1,100,2))
        print('-'*(n-i)*2,end="")
        print(al_list[n+(n-1):n+(n-1)-odd[k]:-1],end="")
        ri_list=ri_list+al_list[n+(n-1):n+(n-1)-odd[k]:-1]
        k+=1
        print(ri_list[-2::-1],end="")    
        print('-'*(n-i)*2,end="\n")
    l=0
    for i in range(1,n):
        print('-'*(i)*2,end="")
        odd=list(range(1,100,2))
        print(al_list[n+(n-1):odd[l]:-1],end="")
        print(al_list[odd[l+2]:n+(n)],end="")
        if i<n-1:
            print('-'*(i)*2)
        else:
            print('-'*((i)*2-1))
        l+=1

if __name__ == '__main__':
    n = int(input())
    print_rangoli(n)
