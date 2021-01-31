# Assignment--#include <iostream>
#include <string>
using namespace std;

int main()
{    const int vat=12;


    cout << "WELCOME TO INF SUPERMARKET" << endl;
    cout<<"Two things are done in this Supermarket"<<endl;
    cout<<"a.Purchasing an item"<<endl;
    cout<<"b.Make enquiries"<<endl;

    string name;
    cout<<"What is your name?"<<endl;
    cin>>name;



    cout<<"Items to be sold"<<endl;
    cout<<"Printer"<<endl;
    cout<<"Phone"<<endl;
    cout<<"Table"<<endl;



    int id;
    cout<<"What is your Unique Id"<<endl;
    cin>>id;


    cout<<"What do you want to buy(one item at a time)"<<endl;
    string buy;
    cin>>buy;


    string a="printer";
    string b="phone";
    string c="table";

    double printer=90;
    double phone=60;
    double table=20;
   double totalcost,totalamountpaid,balance;


    cout<<"Please enter the quantity you want to buy?"<<endl;
    int quantity;
    cin>>quantity;

    cout<<"how much do you have on you?"<<endl;
    int moneynow;
    cin>>moneynow;


    if( moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"You are not eligible to purchase any item"<<endl;

    }
        else if(buy=="printer" ){
            totalcost=(quantity*printer);

           cout<<"The total cost is: "<<totalcost<<endl;
            totalamountpaid=totalcost+vat;
            cout<<"Total amount to be paid with vat: "<< totalamountpaid<<endl;

            balance=moneynow-totalamountpaid;

            cout<<"Your balance after payment: "<<balance<<endl;


       cout<<"--------RECEIPT OF INF SUPERMARKET--------"<<endl;
       cout<<"               Customer name:           "<<name<<endl;
       cout<<"           Customer's Unique Id:        "<<id<<endl;
       cout<<"              Item bought:              "<<buy<<endl;
       cout<<"            Quantity bought:            "<<quantity<<endl;
       cout<<"               Vat amount:              "<<vat<<endl;
       cout<<"               Total Cost:              "<<totalcost<<endl;
       cout<<"            Total amount paid:          "<<totalamountpaid<<endl;
       cout<<"                 Balance:               "<<balance<<endl;

       cout<<"Thank you for transacting with us our dearest custom, we hope to see you again"<<endl;
}

       if( moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"You are not eligible to purchase any item"<<endl;

    }
        else if(buy=="phone" ){
            totalcost=(quantity*phone);

           cout<<"The total cost is: "<<totalcost<<endl;
            totalamountpaid=totalcost+vat;
            cout<<"Total amount to be paid with vat: "<< totalamountpaid<<endl;

            balance=moneynow-totalamountpaid;

            cout<<"Your balance after payment: "<<balance<<endl;


       cout<<"--------RECEIPT OF INF SUPERMARKET--------"<<endl;
       cout<<"               Customer name:           "<<name<<endl;
       cout<<"           Customer's Unique Id:        "<<id<<endl;
       cout<<"              Item bought:              "<<buy<<endl;
       cout<<"            Quantity bought:            "<<quantity<<endl;
       cout<<"               Vat amount:              "<<vat<<endl;
       cout<<"               Total Cost:              "<<totalcost<<endl;
       cout<<"            Total amount paid:          "<<totalamountpaid<<endl;
       cout<<"                 Balance:               "<<balance<<endl;

       cout<<"Thank you for transacting with us our dearest custom, we hope to see you again"<<endl;

}
            if( moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"You are not eligible to purchase any item"<<endl;

    }


        else if(buy=="table" ){
            totalcost=(quantity*table);

           cout<<"The total cost is: "<<totalcost<<endl;
            totalamountpaid=totalcost+vat;
            cout<<"Total amount to be paid with vat: "<< totalamountpaid<<endl;

            balance=moneynow-totalamountpaid;

            cout<<"Your balance after payment: "<<balance<<endl;


       cout<<"--------RECEIPT OF INF SUPERMARKET--------"<<endl;
       cout<<"               Customer name:           "<<name<<endl;
       cout<<"           Customer's Unique Id:        "<<id<<endl;
       cout<<"              Item bought:              "<<buy<<endl;
       cout<<"            Quantity bought:            "<<quantity<<endl;
       cout<<"               Vat amount:              "<<vat<<endl;
       cout<<"               Total Cost:              "<<totalcost<<endl;
       cout<<"            Total amount paid:          "<<totalamountpaid<<endl;
       cout<<"                 Balance:               "<<balance<<endl;

       cout<<"Thank you for transacting with us our dearest custom, we hope to see you again"<<endl;
}

    return 0;
}
