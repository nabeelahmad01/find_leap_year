# find_leap_year
How to find leap year?


class Leap{
void tleap(int year){
var leaplist=[];
var notleap=[];
for(var i=year;i<=2080; i++){
if(i % 4==0){
leaplist.add(i);
}
else{
notleap.add(i);
}

}
print('following are leap years');
    print(leaplist);
    print("followings are nor leaps year");
    print(notleap);
}
}
