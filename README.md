#include<stdio.h>
char main(){
    char Fingerprint,pincode;
    printf("Place your fingerprint here:");
    scanf("%c",&Fingerprint);
    if(Fingerprint=='1'){
    printf("Fingerprint matched and display clients name");
    printf("\n\nEnter Your Pin Code");
    scanf("%c",&pincode);
    
}
else{
    printf("sorry,Fingerprint not matched");
}
}
