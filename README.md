# fraction
The use of common fractions

// - - - - - конструкторы\n
fraction()\n
fraction(int)
fraction(double)
fraction(int, int)
fraction(double, double)
fraction(int, double)
fraction(double, int)
// - - - - - ввод данных
void set()
void set(int)
void set(int, int)
void set(double) {
void set(double, double)
void set(int, double)
void set(double, int)
// - - - - - получение данных
string get()
string get_double()
string get_int()
// - - - - - математические операторы сложения
fraction operator + (fraction)
fraction operator + (int)
fraction operator + (double)
fraction operator += (fraction)
fraction operator += (int)
fraction operator += (double)
// - - - - - математические операторы вычитания
fraction operator - (fraction)
fraction operator - (int)
fraction operator - (double)
fraction operator -= (fraction)
fraction operator -= (int)
fraction operator -= (double)
// - - - - - математические операторы умножения и деления
fraction operator * (fraction)
fraction operator *= (fraction)
fraction operator / (fraction)
fraction operator /= (fraction)
// - - - - - логические операторы сравнения
bool operator > (fraction)
bool operator < (fraction)
bool operator >= (fraction a)
bool operator <= (fraction a)
bool operator == (fraction a)
bool operator != (fraction a)
bool operator > (double)
bool operator < (double)
bool operator >= (double)
bool operator <= (double)
bool operator == (double)
bool operator != (double)
bool operator > (int)
bool operator < (int)
bool operator >= (int)
bool operator <= (int)
bool operator == (int)
bool operator != (int)
// - - - - - операторы присваивания
fraction operator = (fraction)
fraction operator = (double)
fraction operator = (int)
