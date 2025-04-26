In my previous version of A Fibonacci Clock, the Minutes and Seconds were counted one at a time, by ones, in the Large Rectangles on the Left Side, until they reached a threshold of 11.

At that point, the appropriate Large Rectangle on the Left Side was cleared of color, and one of its four external squares was appropriately colored to indicate 12, 24, 36 or 48 increments in time. Once it reached 11 in the appropriate Large Rectangle on the Left, and 48 in its external square, that level was cleared of color and the next higher level was updated.

My previous version is available here:

https://qb45.org/files.php?action=showfile&id=2154

In my new version, instead of using four external squares to the right of the Large Fibonacci Rectangles for the minutes and seconds track of time, they have been replaced with single smaller external Fibonacci Rectangles to the right of the Large Fibonacci Rectangles for the minutes and seconds track of time. This new version is also accurate to the local time's second like my original version.

In my New Version, the Minutes and Seconds are counted by ones, in the appropriate Large Rectangle on the Left side until reaching a threshold of 9.

At that point, the appropriate Large Rectangle on the Left Side is cleared of color, and the appropriate external smaller Fibonacci rectangle on the right side is appropriately colored with a value of 10 - depending upon the size of each of its inner squares. (A 1x1 square colored = 10. A 2x2 square = 20. A 3x3 Square = 30. The squares in the smaller external Fibonacci Rectangle can be combined with color until reaching a value of 50 (3x3 square + 2x2 square), at which time everything on that level is cleared of color and the next higher level is updated.

My new version is available here:

https://qb45.org/files.php?action=showfile&id=2174

Here is a link to view my new JavaScript File Running from 12:40:47 PM to 12:50:08 PM, with the time shown at the top of the video:

https://drive.google.com/file/d/1NimRzUwpSAPBZI0P3MYlHeiFfyi-svQ3/view?usp=drivesdk

A Screenshot showing my New Version display at 1:19:39 PM:

![image](https://github.com/user-attachments/assets/0adbc1bb-98e3-466c-b527-28e20af0afe6)

A Screenshot showing my New Version display at Midnight:

![image](https://github.com/user-attachments/assets/0d41ee78-a4b2-40cd-8481-420c14180fc3)

At Noon, the display would be the same, except the PM Indicator Square would be colored Red.
