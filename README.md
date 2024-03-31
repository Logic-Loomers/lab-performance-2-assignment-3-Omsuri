[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Fmb6W2KK)
Design a C++ program for an employee payroll system. Create classes for Employee and Payroll. Users can add employees, enter hours worked, calculate salaries, and generate payroll reports.


#include<iostream>
using namespace std;

class locate{
    long long int isbn[5]={2125461120084,2357316769488,1021057746565,7485266284736,1212120353427};
    string book [5]={"Republic","Gathering Storm","Alice in Wonderland","The Great Gatsby","French Revolution"};
    string author[5]={"Plato","Winston Churchill","Lewis Carrol","F. Scott Fitzgerald"," Thomas Carlyle"};
    long long int isbn_no;

    public:
        void get(){
            cout<<"enter the ISBN number of the book that you want : "<<endl;
            cin>>isbn_no;
            cout<<endl;
        }
        void locates(){
            int n=0;
            for(int i=0;i<5;i++){
                if(isbn_no==isbn[i]){
                    n=1;
                    cout<<"Your book : "<<book[i]<<endl;
                    cout<<"Author : "<<author[i]<<endl;

                    break;
                    
                    
                }
                
                
            }
            if(n==0){
                    cout<<"BOOK NOT FOUND ERROR 404 :("<<endl;
                }
        }
};
int main(){
    cout<<"Om suri"<<endl<<"2310997192";
    locate l1
    l1.get();
    l1.locates();
    

    return 0;
}