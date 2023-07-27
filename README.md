# Instagram-DM-Chat-Analysis

## Back Story
Healthtracka is a health tech company in Lagos, Nigeria. Healthtracka offers at-home lab tests as well as virtual doctors' consultations. And they have been running paid ads on Instagram for the past month. This campaign has generated leads (conversations). But Healthtracka needs to know how the conversations ended, the frequently asked questions as well as the number of conversations that ended on a promising note.

## Healthtracka seeks to find out:
<ol>
  <li>How many conversations happened between July 1 and July 23?</li>
  <li>Which day had the most messages?</li>
  <li>How many chat messages mentioned pricing?</li>
  <li>How many chat messages mentioned Healthtracka's Full body check-up test package?</li>
  <li>How many chat messages mentioned Healthtracka's STD test package?</li>
  <li>How many chat messages mentioned Healthtracka's Pre-wedding test package?</li>
</ol>

## My Process
<ol>
  <li>Download the chats from Instagram.</li>
  <li>Add all chat files into one folder: Instagram stores each chat as a file in a different folder, so as part of the data transformation process, I put all the chats in one folder.</li>
  <li>Convert each file into a dictionary. Instagram automatically exports the chats in JSON dictionaries, I merged all the chats into a while and saved the chats as dictionaries. Each conversation became a dictionary.</li>
  <li>I renamed the column names to structure the day as well as convert timestamp values into regular time and date.</li>
  <li>I filtered out the irrelevant dates. I only needed data from July 1-23.</li>
  <li>For analysis I made use of NLTK to identify keywords as well as the sentiment score of each of the messages the leads sent to us</li>
</ol>
