# secondclean-trial
A simple demonstration of C++ generic typename::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::



template < typename T >

T myname ( T a , T b ) {

    return ( a > b) ? a :b;
}

int main () {
   
   cout << myname < int > ( 3, 4) << endl;
   cout << myname < char> ('a', 'z') << endl;
   cout << myname <std::string> ("Hello", "Hello" ) << endl;
   
   
   
   
}
