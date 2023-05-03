-------README FOR STUDY BUDDY-------

Study Buddy is a mobile app that allows students to find their classmates and create study groups with their fellow peers based on similar classes, majors, colleges, etc. Students can also purchase tutoring sessions and study guides from other students using the app.
I implemented Google Firebase (for secure login, data management, and chat functionality between the users), Stripe API ( for the payment services for the study guides and tutoring sessions), and Recombee API (to recommend the most suitable study partners for the user).

The following API's were used for this: 

Recombee API: Using the Recombee API and database to store users' majors, class standings, colleges, and courses and to make partner recommendations to these users. I have made calls to Recombee in the account creation process, editing profile process, and recommendation making process. If you are wondering about the database, 
		please contact me at ansh.gupta.gr@dartmouth.edu. If you create a Recombee account on https://www.recombee.com/, I can then add invite your account to view/edit my Recombee project. Note: our free recombee trial ends around December 26, 2021. 
		
Stripe API: Make sure to run the NodeJS server that can be found in the /Server subdirectory of this zip file. Once that is running, Stripe payments will work, but only on the Android emulator. This is because the server is only hosted locally. You must be on that computer on an Android Virtual Device in order to make the payments in this app.

Firebase:
For assistance with firebase contact khalid75@bu.edu
your sha1 key was added to our firebase project, in case you can't log in, try running it using the apk provided in the file.
