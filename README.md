# Test-Case-Samples
Below are some Test Case samples that I wrote while working on previous projects.
..............
*Title	Test login with correct credentials
Description	Check if the login works when a person uses a correct user/pass.
Steps to reproduce	1. Go to www.emag.com/login
	2. Add a correct user/pass
	3. Press Login button
Expected result	User should be able to login and is taken to his profile page.
Test data	User: Voicu & Pass: 21333
Title	Test login with incorrect credentials
Description	Check if the login works when a person uses a incorrect user/pass.
Steps to reproduce	1. Go to www.emag.com/login
	2. Add a incorrect user/pass
	3. Press Login button
Expected result	The user should not be able to login. An error should appear.
Test data	User: Voicu & Pass: 21333
Title	Test login without credentials
Description	Check if the login works without credentials.
Steps to reproduce	1. Go to www.emag.com/login
	2. Press Login button
Expected result	The user should not be able to login. An error should appear.
Test data	-
Title	Test the Remember Me button 
Description	Check if the Remember Me button it's working when a person uses a correct user/pass.
Steps to reproduce	1. Go to www.emag.com/login
	2. Add a correct user/pass
	3. Check the"Remember Me button 
	4. Press Login button
	5. Press Log out button
	6. Press Login button
	7. Check if the credentials are in the field
	8. Press Login button
Expected result	The user should have the credentials in the field and is taken to his profile page.
Test data	User: Voicu & Pass: 21333
Title	Test  the Search button 
Description	Check if the Search button works.
Steps to reproduce	1. Go to www.emag.com/login
	2. Add the word "whiskey" in the search button
	3. Press the search button
Expected result	The user should be taken to the whiskey page.
Test data	-
Title	Test if the autocorrect works in the search button
Description	Check if the autocorrect works in the search button.
Steps to reproduce	1. Go to www.emag.com/login
	2. Add the word "whi" in the search button
	3. Press the keyboard  key "->" when the word "whiskey" appears
Expected result	The user should have the word "whiskey" in the search button.
Test data	-
Title	Test the Search button with incorrect credentials 
Description	Check if the Search button works with incorrect credentials.
Steps to reproduce	1. Go to www.emag.com/login
	2. Add the word "dadasdsada" in the Search button
	3. Press Search button
Expected result	The user should be taken to the Search page.
Test data	-
![image](https://user-images.githubusercontent.com/58988246/183147082-6f9e7b65-94aa-4004-816a-2b936a9d5256.png)

