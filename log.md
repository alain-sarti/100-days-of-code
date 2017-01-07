# 100 Days Of Code - Log

### Day 1: December 30th, Friday

**Today's Progress**: I've set up everything to start right away.

**Thoughts** I've tried to finish so many projects and never succeeded. Maybe this challenge will help me finally finish a project :)

**Link(s) to work**
1. [Initial Blog post](http://technophilia.de/2016/12/30/starting-the-100-days-of-code-challenge/)
2. [First App](https://github.com/alain-sarti/letmesleepalarm)

### Day 2: December 31th, Saturday

**Today's Progress**: The App can show a notification, and it can also play a sound. Need to add a way to stop it tomorrow ;)

**Thoughts** Showing local notifications is really a lot easier than I thought it would be ;)

**Link(s) to work**
1. [Gist I looked at to start with notifications](https://gist.github.com/BrandonSmith/6679223)
2. [Stackoverflow question I looked at to play a sound](http://stackoverflow.com/questions/24766775/android-get-default-or-currently-set-alarm-sound-tone)
3. [Android SDK Dokumentation for exact AlarmManager settings](https://developer.android.com/reference/android/app/AlarmManager.html#setExact(int, long, android.app.PendingIntent))

### Day 3: January 1st, Sunday

**Today's Progress**: It took a little bit longer to be able to stop the alarm sound. But I got it fixed, a Singleton Pattern for access to the Ringtone was the answer.

**Thoughts** I definately need to structure the app way better. But I like the approach so far, to build it in stages.

**Link(s) to work**
1. [Let me Sleep Alarm](https://github.com/alain-sarti/letmesleepalarm)

### Day 4: January 2nd, Monday

**Today's Progress**: I did a lot of trial and error today. But I finally got what I wanted to work. The app will now start it's stop activity even if the device is locked. Tomorrow I'll add the function of closing the activity after stopping the alarm.

**Thoughts** Sometimes things can be really easy ... if you knew what to lock for ;)

**Link(s) to work**
1. [Let me Sleep Alarm](https://github.com/alain-sarti/letmesleepalarm)
2. [Stackoverflow question for showing an activity on a locked screen](http://stackoverflow.com/questions/19003568/android-galaxy-s4-activity-that-is-visible-over-lock-screen?rq=1)

### Day 5: January 3rd, Tuesday

**Today's Progress**: Allright, ready for the first night test. Added the input fields. Stoping the Alarm also closes the activity. The alarm also plays if the phone is set to vibrate.

**Thoughts** It's sometimes rather scary, what you can do with your app like declaring the sound you play to be an alarm and therefore ignoring the user's settings.

**Link(s) to work**
1. [Let me Sleep Alarm](https://github.com/alain-sarti/letmesleepalarm)
2. [Stackoverflow question for playing an alarm tone if phone is silent](http://stackoverflow.com/questions/24306284/want-to-play-the-ringtone-in-vibration-mode)
3. [Android Support Blog announcing interesting material design additions](https://android-developers.googleblog.com/2015/05/android-design-support-library.html)

### Day 6: January 4th, Wednesday

**Today's Progress**: I was woken up by my app :) Today was a slow day, I therefore started the second app, but there is nothing really to see, yet.

**Thoughts** Tomorrow will be my day off for the week.

**Link(s) to work**
1. [Let me Sleep Alarm](https://github.com/alain-sarti/letmesleepalarm)
2. [SWRPG Helper Droid](https://github.com/alain-sarti/swrpgHelperDroid/)

### Day 7: January 5th, Thursday

**Today's Progress**: Change of plans, my day off will be tomorrow. Today, I added I18n to both apps. I will add a blog entry for the ionic 2 part, because the instructions you find in the web are mostly outdated.

**Thoughts** I can't wait for ionic 2 to become stable ... 

**Link(s) to work**
1. [Let me Sleep Alarm](https://github.com/alain-sarti/letmesleepalarm)
2. [SWRPG Helper Droid](https://github.com/alain-sarti/swrpgHelperDroid/)

### Day 8: January 7th, Saturday

**Today's Progress**: I added the display of a notification to show the intended alarm time. But I couldn't quite figure out how to cancel the alarm on a click on the notification. Maybe it's the time ;)

**Thoughts** I will have to look how an alarm app can distinguish between different alarms and shut them down ...

**Link(s) to work**
1. [Let me Sleep Alarm](https://github.com/alain-sarti/letmesleepalarm)
2. [SWRPG Helper Droid](https://github.com/alain-sarti/swrpgHelperDroid/)