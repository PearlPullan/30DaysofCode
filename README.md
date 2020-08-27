# 30DaysofCode
Points noticed everyday-
1. from string s ---- int n= s.length() | if char c ----- int n= strlen(c);
2. return type should be same as function type --- int / long are differently used.
3.size of vector can be calculated by int n=a.size();
4.A 2D vector is a vector of vector. Like 2D arrays, we can declare and assign values to 2D matrix
vector<vector<int> > vect={ { 1, 2, 3 }, 
                               { 4, 5, 6 }, 
                               { 7, 8, 9 } }; 
   for (int i = 0; i < vect.size(); i++)
       for (int j = 0; j < vect[i].size(); j++) 
            cout << vect[i][j] << " "; 
        cout << endl;
Like Java’s jagged arrays, each row of 2D vector can contain different number of columns.
  
  5. Finding in vector 
  vector<int>::iterator it;
   it = std::find (magazine.begin(), magazine.end(), note[i]); 
  
  6. A stringstream associates a string object with a stream allowing you to read from the string as if it were a stream (like cin).
Basic methods are –
clear() — to clear the stream
str() — to get and set string object whose content is present in stream.
operator << — add a string to the stringstream object.
operator >> — read something from the stringstream object,
