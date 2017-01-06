# 100 Days Of Code - Log

### Day 1: 29 December 2016

**Today's Progress**: Forked 100 Days of Code and updated outdated WooCommerce files on thecleft.org

**Thoughts:** Pretty boring work. I'm fairly confident that I have more files than needed duplicated, but they are all updated

**Link to work:** [Cleft Repository](https://github.com/DustinHartzler/TheCLEFT/commit/2733f569770d2cf39a49ac5677095e0b818585ff)

### Day 2: 30 December 2016

**Today's Progress**: Started working on As Heard On plugin and I fixed the bug that the data wasn't be deleted from the database.

**Thoughts**: Looking at the code, I'm impressed I was able to modify a Testimonial plugin to get it to work like it has. There's a lot to refactor and make the code simpler.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/3ae18b85dd2208a690456a1135633c7323017627)

### Day 3: 31 December 2016

**Today's Progress**: Added new if statement to check if 'ppg_version' option is set to 0.5. The if statement will look for all the previous options and move them into an array (hopefully tomorrow!)

**Thoughts**: Spent time thinking / planning on how to save current options to a new serialized array. No reason that a small plugin like AHO, should be adding more than 2 or 3 rows to the table. Currently there's more than 20!

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/fc5d79d15804e5eec18ae811496422141f820566)

### Day 4: 01 January 2017

**Today's Progress**: Created `legacy.php` to add all the code to remove old options from WordPress database

**Thoughts**: Really important to set a plugin up initially correctly. I'm finding it's very tedious to remove options, but save the settings in the database.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/b5514b245aee953ea78651ea72074c86b771157c)

### Day 5: 02 January 2017

**Today's Progress**: Removed a nevercalled function that was supposed to remove settings from the database. Also, moved the location of the 'help' menu so it was visible on all pages and made the footer less bulky

**Thoughts**: Worked solidly for an hour and didn't accomplish much. Starting to see why software development takes so long! Need to work on calling data from new serialized arrays tomorrow.

**Links to work**: [#](https://github.com/DustinHartzler/As-Heard-On/commit/2dbbd5b9c7e513930e9a57927105c7d5c89fe265), [#](https://github.com/DustinHartzler/As-Heard-On/commit/8a0e92a16b32d4e9dc23a3e7681f68505db585c2), [#](https://github.com/DustinHartzler/As-Heard-On/commit/54b90a1da2a637f0ace338c18ff13f21561e49a1)

### Day 6: 03 January 2017

**Today's Progress**: Have one option running on serialized data.

**Thoughts**: Slow moving today. Started to move variables to serialized array. Much harder than expected.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/7f2b3f02dd98ddb5b8f6b574aed6ee19726d569d)

### Day 7: 04 January 2017

**Today's Progress**: Added 3 new variables to the array and tested to make sure the options were working correctly. `showlink`, `image_width`, and `image_height` are now working as well as `linktext` from late last night's bonus session

**Thoughts**: Made much more progress today versus yesterday, yay! Still have a lot more to do to simplify the code and get all the pieces working efficiently. Perhaps by the end of the month I'll be able to start adding new features :)

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/041a1be329512826ce36681ab9ab84f73bb1d81d)

### Day 8: 05 January 2017

**Today's Progress**: Made more progress moving data to the serialized array. Only a handful more and this task will be complete!

**Thoughts**: I thought I'd get everything finished today, yet, when I went to start working on the page settings, I realized all of the widget settings were being erased. Two steps forward and one back. Both panels are working now.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/1cf1a50d65f0c69b271cf35ed35aaf06a174ff15)

### Day 9: 06 January 2017

**Today's Progress**: Finished moving all variables to serialized array.

**Thoughts**: Again, it was a bit tricker than I thought it would be and now I know why it's so important to set things up properly the first time :) Tomorrow I'll do a bit of testing and see how well things work when I update the plugin to the new version.

**Link to work**: [As Heard On](https://github.com/DustinHartzler/As-Heard-On/commit/b34215944f1d2b42f492aef36a5df6cd94ecdd5e)
