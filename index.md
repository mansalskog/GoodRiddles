# Good Riddles
This is a collection of (mostly mathematical) riddles which I enjoy,
arranged in order of increasing difficulty.

## 1
There are two trains travelling in opposite directions on the same track,
each with a speed of 100 miles per hour. They start out at a
distance of 200 miles from each other.
At the start, there is a fly just in front of one train, flying towards
the other at a speed of 150 miles per hour. When it reaches
the other train, it turns around and flies back at the same speed.
It continues in this way until the two trains meet in the middle.
How long will the fly have travelled in total by then?

## 2
There is a remote island with 200 people living on it, all of which
are perfect logicians.
The people cannot speak to each other or communicate in any way.
There are 100 people with blue eyes, and 100 people with brown eyes.

However, the inhabitants do not know this.
Although they can see all other inhabitants, they cannot (yet) know the
colour of their own eyes.
For all they know, there could be 100 people with blue eyes, 99 people with
brown eyes, and one person with green eyes (themselves).

Each night, a boat comes to the island.
Any person who has figured out the colour of their own eyes is allowed to
leave on the boat.
They cannot guess; they must know the colour of their eyes for certain.

One day, an explorer arrives to the island, and says to all the inhabitants,
"I can see someone who has blue eyes".
We call the night after this happens night number one.
The question is then, how many people will leave the island, and on which nights?

## 3
A scientist has given you and your friend a task to test your collaboration skills.
On each of the 64 tiles of a chessboard a coin is placed, either heads up or tails up.
Under one of the coins a key is hidden.

The scientist will reveal the key to you while your friend is in another room.
You will then be allowed to flip exactly one of the coins of your choice, turning
it from heads to tails or vice versa.
Then you will leave the room and you friend will be allowed to enter, given the
task of finding the key by only looking at the state of the coins.

You are allowed to figure out a strategy together with your friend beforehand.
However, the scientist must also know this strategy, and is allowed to place
the coins and key in any way, as to minimise your chance of success.
Is it possible to come up with a strategy that works every time?

Now suppose that the side length of the chessboard is not 8 squares, but
instead *n* squares. For which natural numbers *n* is it possible to find a
succeeding strategy?

## 4
For which natural numbers *n* does a surjective function
from **R**^n^ to the strictly positive real numbers exist? <br/>
That is, a function *f* such that for all *y* &gt; 0,
there exist some real *x*~1~,*x*~2~,...,*x*~n~
such that *f*(*x*~1~,*x*~2~,...,*x*~n~) = *y*.

## 5
What is the smallest array on the form <br/>
&emsp; *S* = *u*~1~ &otimes; *u*~2~ &otimes; *u*~3~ &otimes;
+ *v*~1~ &otimes; *v*~2~ &otimes; *v*~3~, <br/>
such that &mid;&mid;T-S&mid;&mid; is minimal,
where &mid;&mid;&middot;&mid;&mid; is the Euclidean norm,
&otimes; is the tensor product, <br/>
&emsp; *t*~112~ = *t*~121~ = *t*~211~ = 1 <br/>
and <br/>
&emsp; *t*~111~ = *t*~122~ = *t*~212~ = *t*~221~ = *t*~222~ = 0?

## 6
Note that <br/>
&emsp; &int; ~0~^&infin;^ sin(*x*)/*x* d*x* = &pi;/2, <br/>
&emsp; &int; ~0~^&infin;^ sin(*x*)/*x* sin(*x*/3)/(*x*/3) d*x* = &pi;/2, <br/>
&emsp; &int; ~0~^&infin;^ sin(*x*)/*x* sin(*x*/3)/(*x*/3) sin(*x*/5)/(*x*/5) d*x* = &pi;/2. <br/>
Prove that <br/>
&emsp; &int; ~0~^&infin;^ &prod;^*n*^~*k*=0~ sin(*x*/(2*k*+1))/(*x*/(2*k*+1)) d*x* = &pi;/2 <br/>
for all natural *n*.

## 7
In the yard of a farmer there is a circular fence of radius *R*.
At one point on the boundary of the fence there is a post, and from the post
there is a leash of length *L* attached to a goat.
The goat can move around on the grass and eat it, however it cannot jump over
the fence.
When the goat goes on the other side of the circle, relative to the post, the
leash wraps around the fence, following its boundary.
What is the total area of grass that the goat can eat?

Now suppose the goat is on the inside of the fence.
The farmer wants the goat to be able to eat exactly half of the area of the
grass inside the fence.
What length *L* should be chosen for the leash?

## 8
You are arranging a party for your friends. In doing this you have to decide
how many guests to invite. To optimise the socialising, you have figured out
a slightly odd requirement. You would like there to be either <br/>
&emsp; &bull; at least five persons that all know each other, <br/>
or <br/>
&emsp; &bull; at least five persons that all don't know any of the others. <br/>
However, being the frugal type, you want to invite as few people as possible.
What is the smallest number of people you have to invite?

<details>
    <summary>Click here for a hint.</summary>
    The number is greater than 40, but smaller than 50.
</details>

## 9
An eccentric baron wants to build a mansion, and has hired you to do it.
However, there is an unusual requirement: all the bricks used to build it
should have widths, lengths and heights which are an integer number of inches.
The three diagonals along the sides of the bricks should also be integers,
as should the diagonal through the brick between opposing corners.
What should the width, length and height of such a brick be?

<details>
    <summary>Click here for a hint.</summary>
    The shortest side of the brick must be longer than the distance to the sun.
</details>

## 10
You are given a set of domino tiles, but instead of dots they have letters
written on them. The goal is to arrange these tiles such that the word which
is read on the top half of the tiles, is the same as the word which is read on
the bottom half. For instance, given tiles with the letters A/A, A/AB, BB/B
you can construct:
<table>
    <tr>
        <td>A</td> <td>BB</td> <td>A</td>
    </tr>
    <tr>
        <td>AB</td> <td>B</td> <td>A</td>
    </tr>
</table>
You are allowed to use multiple of any tile, e.g., adding an extra A/A
tile to the end of the above solution would also result in a valid solution.
You have an unlimited number of tiles of each type, and can construct any word
you choose (of finite length).

Finding a solution is clearly not always possible.
Take for example the set of tiles with letters A/A and A/B.
Can you figure out a method that, for any set of bricks, determines if a
solution exists?

<style>
h1, h2 {
    text-align: center;
}
body {
    width: 50%;
    margin: 0 auto;
}
td {
    border: 1px solid black;
    padding: 2px;
    text-align: center;
}
table {
    border-spacing: 2px 0;
    margin: 0 auto;
}
</style>
