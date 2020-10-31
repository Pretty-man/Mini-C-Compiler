#include <bits/stdc++.h>

using namespace std;
//词法分析程序
//首先定义种别码
/*
第一类：标识符   letter(letter | digit)*  无穷集
第二类：常数    (digit)+  无穷集
第三类：保留字(32)
auto       break    case     char        const      continue
default    do       double   else        enum       extern
float      for      goto     if          int        long
register   return   short    signed      sizeof     static
struct     switch   typedef  union       unsigned   void
volatile    while

第四类：界符  ‘/*’、‘//’、 () { } [ ] " "  '
第五类：运算符 <、<=、>、>=、=、+、-、*、/、^、

对所有可数符号进行编码：
<$,0>
<auto,1>
...
<while,32>
<+，33>
<-,34>
<*,35>
</,36>
<<,37>
<<=,38>
<>,39>
<>=,40>
<=,41>
<==,42>
<!=,43>
<;,44>
<(,45>
<),46>
<^,47>
<,,48>
<",49>
<',50>
<#,51>
<&,52>
<&&,53>
<|,54>
<||,55>
<%,56>
<~,57>
<<<,58>左移
<>>,59>右移
<[,60>
<],61>
<{,62>
<},63>
<\,64>
<.,65>
<?,66>
<:,67>
<!,68>
"[","]","{","}"
<常数99  ,数值>
<标识符100 ，标识符指针>


*/
static char reserveWord[32][20] = {
    "auto", "break", "case", "char", "const", "continue",
    "default", "do", "double", "else", "enum", "extern",
    "float", "for", "goto", "if", "int", "long",
    "register", "return", "short", "signed", "sizeof", "static",
    "struct", "switch", "typedef", "union", "unsigned", "void",
    "volatile", "while"
};
static char operaterWord[36][10] = {
    "+", "-", "*", "/", "<", "<=", ">", ">=", "=", "==",
    "!=", ";", "(", ")", "^", ",", "\"", "\'", "#", "&",
    "&&", "|", "||", "%", "~", "<<", ">>", "[", "]", "{",
    "}", "\\", ".", "\?", ":", "!"
};

int main(int argc,char argv[])
{
    char resourceProject[10000];
    char token[20] = { 0 };
    int syn = -1, i;//初始化
    int pProject = 0;//源程序指针
    int fin;
    if((fin=open(argv,0))<0)
    {
         cout << "can't open this file";
         exit(0);
    }
    return 0;
}
