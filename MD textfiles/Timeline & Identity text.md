List of contents:
- Timeline to fluency
- Super detailed timeline

## Timeline to fluency
Day 1-14: [Hiragana](https://www.tofugu.com/japanese/learn-hiragana/)  
Day 15-30: [ Katakana](https://www.tofugu.com/japanese/learn-katakana/)  
Day 31-40: Read [Tae Kim's guide to Japanese grammar (p.29-81)](https://www.guidetojapanese.org/grammar_guide.pdf)  
Day 41-341: Install [Anki](https://apps.ankiweb.net/) and do the [Kaishi 1.5k deck](https://ankiweb.net/shared/info/1196762551)  
Day 342: Start [Mining with Yomitan](https://github.com/yomidevs/yomitan) to mine new words you encounter    
Day 365: 1 Year anniversary (vocabulary: ~1730 words ~N4 level)  
> Move onto native content, no more beginner content  
> Start talking in Japanese language Exchange discord servers  

Year 2-3: Continue mining and do 10 new cards a day  
Second Anniversary: vocabulary: ~5300 words ~N3 level  
> Set Yomitan to Monolingual  
> Start talking with Japanese Natives  

Third anniversary: vocabulary: ~9030 words ~N2 level  
Day 826: vocabulary: ~10k words ~N1 level, Start of Intermediate Plateau  
Day 827: Premade decks in addition to Mining  
> Kanji Kentei Level 10 to Level 1 to have coverage of all Kanji (stop after Pre-1) 15 Kanji a day  
> Grammar Anki deck (2 Grammar points per day) or [Bunpro](https://bunpro.jp/)

Fourth anniversary: vocabulary: ~15650 words ~N1 level  
> Increase mining to 15 new words a day  
> Finished with Grammar deck after half a year  

Fifth anniversary: vocabulary: ~20,000 words ~Everyday fluency  


----

# Identity

Japanese learner since 2020

Macroeconomics major

19 y/o

# Interests

## Languages

### Japanese

I've been actively studying Japanese for the past 4 years and like to read historic documents about Japanese Buddhism and watch YouTube videos about history. I also do traditional calligraphy on the side

### Spanish

I was forced by my school to take on Spanish. Studying for 3 years now

### Chinese

Had the opportunity to go to China on a student exchange, so I started studying Mandarin in December 2023

## Music

I can recommend [pami](https://www.youtube.com/channel/UCvWaqKFGpxCty8zMa0NoNiA), [Cateen](https://www.youtube.com/channel/UC_QG8miwKHFNuWY9VpkrI8w) and [Fujii Kaze](https://www.youtube.com/channel/UCNIy6zQyP7SuLEIaiwymfUA)

## Games

Former Genshin addict, Hitman III, Doom Eternal, Besiege

# Profiles

Feel free to message me if you have questions about Japanese and how to advance

Discord: julian_riku

MAL: [JRiku](https://myanimelist.net/profile/JRiku)

Github: [JRiku](https://github.com/JRiku)

# Active Projects

[Japanese Study guide](https://jriku.github.io/learnjp/)

# Currently Studying (2025.04.30)

- Kanji Kentei Level 1 (2554/6264)
- Kokuji (111/139)
- Japanese Proverbs (519/7127)
- Four Character Compounds (429/6382)
- Ateji (71/4130)
- Nandoku Kanji (151/598)
- Variant Hiragana forms (51/347)
- Old Kanji forms (155/459)
- Ancient Japanese prefectures (48/68)

# Min-maxxing of Anki

## Settings
I'd recommend watching the Installation and use of Anki guide by [Jouzu Juls](https://www.youtube.com/watch?v=DcY2Svs3h8M), the rest is all my own opinion and what I found useful in 3 years of using Anki

I found that not showing the next review time above answer buttons really helps since you don't consider card times anymore

## Cards

Oftentimes pre-made decks have bad or lacking formatting. Fortunately Anki cards use simple HTML and CSS. If you want to change it you either ask ChatGPT or Deepseek to get it changed (tiresome) or you do like a 4 hour html and css course and it is quite simple to set up.

Some quirks of [Anki html](https://docs.ankiweb.net/templates/intro.html) on the side:

[Field replacements](https://docs.ankiweb.net/templates/fields.html):

{{Field name}} is what you need to add into the html code for it to actually display the field's content and case does matter.

if a field only contains an image then (even though it's not written into the html) you can manipulate it in css via the img functionality.

To change anything about the default text input box you have to use "input{...: !important;}" for it to change anything

[Text to speech functionality](https://docs.ankiweb.net/templates/fields.html#text-to-speech-for-individual-fields):

Works with {{tts language_LANGUAGE-VARIANT:Field name}} and the language has to be specified for it to work(language codes can be found [here](https://www.ibm.com/docs/en/rational-soft-arch/9.6.1?topic=overview-locales-code-pages-supported) for Japanese it is jp_JP)

[Ruby (furigana) functionality](https://docs.ankiweb.net/templates/fields.html#ruby-characters):

Your fields have to be in the format 世[よ]の 中[なか] meaning first the Kanji, then the Kana in brackets and where a new furigana is supposed to start there has to be a space before the Kanji, Yomitan as well as the AJT Japanese add-on do this automatically but there might still be mistakes.

[Dictionary links](https://docs.ankiweb.net/templates/fields.html#dictionary-links):

You can add dictionary links through links like href="https://jisho.org/search/{{field name}}"

## Add-ons

### Editing

#### [1898445115](https://ankiweb.net/shared/info/1898445115) - Advanced Copy Fields

Allows you to switch, replace  and move fields easily

#### [1344485230](https://ankiweb.net/shared/info/1344485230) - AJT Japanese

Allows you to easily add furigana and pitch accent patterns to cards

#### [291119185](https://ankiweb.net/shared/info/291119185) - Batch Editing

Allows you to add information to a specific field or systematically replace the content of a specific field among multiple cards

#### [1374772155](https://ankiweb.net/shared/info/1374772155) - Image Occlusion Enhanced

Allows you to block parts of an image to test yourself

### Appearance

#### [1210908941](https://ankiweb.net/shared/info/1210908941) - Custom Background Image and Gear Icon

Allows you to change your Anki wallpaper from basic grey to a specified image and change the opacity  

##### Setup

After installation a new tab will be available at the top called AnKing, click it and click on Custom Background and Gear Icon --> click on Open Image Folders --> add your preferred wallpaper --> go back to the window and click on the three dots on the right --> select your wallpaper

### Information

#### [1828617820](https://ankiweb.net/shared/info/1828617820) - Kanji Table

Allows you to have an overview over your knowledge of Kanji, sorted quite neatly

#### [1508357010](https://ankiweb.net/shared/info/1508357010) - Review Heatmap

Adds a heatmap graph to Anki's main window, which visualizes your past and future card review activity  

#### [1613056169](https://ankiweb.net/shared/info/1613056169) - Search Stats Extended

Adds tons of new statistics to Anki's deck stat page which can help you identify weakpoints or strongpoints in your reviewing style or help you identify trends (e.g. rising review speed can show that you're doing Anki at the wrong times of the day where you're less concentrated)

#### [613684242](https://ankiweb.net/shared/info/613684242) + [1779060522](https://ankiweb.net/shared/info/1779060522) - True Retention (simplified and standard)

If you hold shift while clicking the stat screen it shows you your true retention for that deck which is more accurate than Anki's Retention based solely on how often you pressed the Again button

### Review

#### [1868980340](https://ankiweb.net/shared/info/1868980340) - AnkiDraw

Allows you to draw and write into your anki card (temporarily) using your mouse or drawing tablet
 (perfect for practicing handwriting)

#### [876946123](https://ankiweb.net/shared/info/876946123) - Pass/Fail

Removes the Again and Easy button from your Anki reviewer thereby forcing you to either decide between knowing the card (pass) or to fail. 
Also: Anki fsrs (scheduling system) is bad with again and easy reviews and schedules them badly, so sticking to fail and good also leads to a better and more accurate algorithm

### Focus

#### [1508357010](https://ankiweb.net/shared/info/1508357010) - Remaining time

Adds a bar to the top that tells you how long you will need to finish your current deck at your current pace

#### [715575551](https://ankiweb.net/shared/info/715575551) - Life Drain

Adds a bar to the bottom that counts down and only refills once you finish your card. Great for pacing yourself and making sure you don't spend too long on one card

##### Setup

If you have a specific time per deck you want to achieve then you should set your total health to your average cards a day multiplied by your card time and set the Answer recover to your desired time per card, when you're faster than desired you will gain life and if you're slower then your life will fall

Also, for visual appeal I would set it to be on the top and be really just like two to three pixels tall and to let it start from 0 on the right

### Gamification

#### [1951446409](https://ankiweb.net/shared/info/1951446409) - Advanced Answer Sounds

Allows you to add custom Sounds that play when you answer a word correct or wrong

#### [231569866](https://ankiweb.net/shared/info/231569866) - Audiovisual Feedback

Makes the edges of your screen flash green or red depending on if you got the card right or wrong

## Anki livesplits

If you realize that you're taking way too long for your Anki and often lose focus then [livesplits](https://livesplit.org/) are the ultimate solution. 

### Setup

Note down your average cards per day and average review time for each of your decks. 
By multiplying these you can find out how long you take on average per day. Now you have to consider if how much you want to shave off of your daily Anki. Livesplit uses cumulative times meaning that split 1 is just one time, split 2 is the time for split 2 + the time of split 1 and so on, so you need to calculate them up. For me personally I limit my anki to 45 minutes for about 650 cards I do per day on average. For that I calculated my average times, gave them to chatGPT and told it to shave off, where I have the fewest cards and to leave time for the bigger decks. That way it's dynamic for you to be able to achieve your goal without constantly falling behind on one deck and then being five minutes too early on another deck. 

After you calculated how long you may take per deck you will want to set up your splits, right click the livesplits application and go on edit splits, then you name them in the order you want to do your decks and put in a new comparison, into that comparison you will want to put your desired times in cumulative form. Hit OK and right click the livesplits application again, then you click on edit layout and add your splits, the detailed timer, the previous segment, the current pace and the graph (set to your comparison).

Boom, you're set to go