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
