# Custom-Captcha
Hey friends, today in this project we will create Custom Captcha in HTML CSS & JavaScript.
Mostly, Captcha is used on the comment or contact form of the websites to restrict robots (bot)
 from commenting on a blog post or sending a message to the admin.
There can be random images or codes in the captcha, and the users must have to 
select correct images or match the codes to complete their task.

In this small project [Custom Captcha in JavaScript], as we can see in the preview image,
 there is an image with the random 6 characters and numbers.
 You can also refresh the captcha code and get a new one using the reload button.

In the input field, you have to enter the captcha codes that are shown on the image.
If your codes matched with the captcha codes, then there is appears a success message else there appears an error message.
If you’ve matched the codes, then after 4 seconds there will be generated a new one captcha code.

let’s understand the basic codes and concepts of this program. 
At first, in the JavaScript file, I have stored all characters and numbers in the array, then inside for loop, using Math.random() function I got 6 random characters from the given array.

And passed these codes or characters in the captcha by adding space between each character.
 After this, I got user-entered values, split them, and joined them with space (‘ ‘) so users don’t need to enter spaces to match the codes.

Once I joined the user values then I matched this user value with the captcha codes.
 If the value is not matched I’ve shown an error message, 
 and if the value is matched I’ve shown a success message and generate the new random codes after 4 seconds using the setTimeout() function.
