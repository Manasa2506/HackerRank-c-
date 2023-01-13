#include <iostream>
#include <string>
#include <sstream>
#include <exception>
using namespace std;

struct BadLengthException : exception 
{
  string s;
  BadLengthException(int n) : s(to_string(n)) {}
  const char *what() const noexcept override 
  {
    return s.c_str();
  }
};
