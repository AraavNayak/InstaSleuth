# InstaSleuth

Ever wanted to unfollow your unfollowers?

Look no further. This program gives you a list of accounts you don't follow back and accounts who don't follow you back on Instagram. This project utilizes Instagram API to fetch followers/followings, and utilizes IO to compare the contents of two lists (one of followers, the other of followings) and output the result.
<hr>
<code>ListComparer.java</code> <i> outputs an ArrayList of elements from a list not present in another list; this can be used to tell you people who have unfollowed you or people you have unfollowed from a certain time. </i>
<br>
<code>obtainLists.js</code> <i> details the Instagram API code necessary to obtain the list of followers/following of a user from the javascript console on instagram.com. This can be used to obtain the lists of followers, followings, as well as lists of people who you don't follow back and people who don't follow you back. </i>
<br>
<code>trueCount.js</code> <i> details the code (to be pasted in Instagram.com console) to obtain the actual count of followers of the specified user. Instagram sometimes doesn't show an accurate follower count, so this can be used to give you that accurate reading of how many followers the specified user actually has </i>
<br>
<code>autoUnfollowUnfollower.js</code>
<br>
<code>doesXFollowMeBack.js</code>

<hr>
<h3>Instructions</h3>
<h6>First change the username in <code>obtainLists.js</code> and <code>trueCount.js</code> to the username of the account you want to run this program on, and then go to Instagram and paste and enter the content of <code>obtainLists.js</code> into the console and then enter copy(followers). Then open a txt file: (1) write the date on the first line, (2) paste (3) if you want to compare your current followers to previous followers, specify the path to each of the txt files in <code>ListComparer.java</code> and run the program (4) Follow my insta/github for more! :D</h6>
<br></br><hr>
<u>More on the Instagram API: </u> <a href="https://stackoverflow.com/questions/32407851/instagram-api-how-can-i-retrieve-the-list-of-people-a-user-is-following-on-ins?answertab=scoredesc#tab-top">https://stackoverflow.com/questions/32407851/instagram-api-how-can-i-retrieve-the-list-of-people-a-user-is-following-on-ins?answertab=scoredesc#tab-top</a>
