## Welcome to dcap's Page
#### This page is for the illustrious **CSE 110** course

##### A Bit About Me
![a pic of me](/img/freedom_scaled.png)

A favorite pic of myself, lightly edited by a friend. You can get it and laugh at it [here](/img/freedom_scaled.png).

* I am currently a UCSD student at Revelle and computer science major
* I enjoy the Latin language and am thinking about pursuing a minor
* My favorite programming language is C. Yep, now that was a good language
* I tend to avoid big name search engines in favor of something a little more privacy-respecting like searx. Learn more [here](https://searx.me/)!

##### Some Quotes
This is my favorite quote:
>It is entirely conceivable that life’s splendour forever lies in wait about each one of us in all its fullness, but veiled from view, deep down, invisible, far off. It is there, though, not hostile, not reluctant, not deaf. If you summon it by the right word, by its right name, it will come. This is the essence of magic, which does not create but summons.

by Franz Kafka

The famous fast inverse square root from *Quake III Arena* (stripped of a comment):
```
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 ); 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```
