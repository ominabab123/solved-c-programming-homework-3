Download Link: https://assignmentchef.com/product/solved-c-programming-homework-3
<br>
5/5 - (2 votes)

●     (80 points) Write a String class which will be a wrapper class to the C style strings. The strings will be of varying lengths and must grow and shrink as necessary. Your String class must implement all the appropriate methods including constructors, assignment, equality operators, the index operator, reverse, indexOf (find), print, and read. I would prefer you not use any of the C  str functions (e.g. strcmp, or strcpy), however you may write them yourself, as static methods, then use them.



●     Class String declaration:class String{public:/// Both constructors should construct/// this String from the parameter sString( const char * s = “”);String( const String &amp; s );String operator = ( const String &amp; s );char &amp; operator [] ( int index );int size();String reverse(); // does not modify this Stringint indexOf( char c );int indexOf( String pattern );bool operator == ( String s );bool operator != ( String s );bool operator ( String s );bool operator &lt; ( String s )bool operator &lt;= ( String s );bool operator = ( String s );/// concatenates this and s to return resultString operator + ( String s );/// concatenates s onto end of thisString operator += ( String s );void print( ostream &amp; out );void read( istream &amp; in );~String();private:bool inBounds( int i ){return i = 0 &amp;&amp; i &lt; len;}char * buf;int len;};ostream &amp; operator &lt;&lt; ( ostream &amp; out, String str );istream &amp; operator ( istream &amp; in, String &amp; str );

●     (20 points) Write a main function which tests each function defined in your class String.<button class="ui mini button product-like-wrap" data-key="Hhi3" data-auth="false"></button>