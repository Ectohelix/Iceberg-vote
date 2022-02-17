# Iceberg-vote
Icicle themed vote system

---Required OBS plugins---

1.) Source Copy - Used to Load The Scenes Easily

https://obsproject.com/forum/resources/source-copy.1261/

2.) Move transition - Used to Move the icicles

https://obsproject.com/forum/resources/move-transition.913/

---Extracting Files---

Unzip them to C:/Vote
There's probably a better way of doing this, or a better place to put these files, but I have no idea what I'm doing.

---Configuring OBS---

Use Source Copy to import OBS-IcebergVote.json, You can copy the filters from the "---Popups" scene to wherever you want to put the vote popup, BUT you'll have to make sure it's reflected/replaced in each of the Vote actions in Streamer.bot
Personally, I'd recommend leaving everything of this category in it's own nested scene.

Configuration of Streamer.bot-

1. Import the IcebergVote_Export JSON file into Streamer.bot
2. Configure (on the Commands page, the below 3 commands):
!askyn - Location: Start - Action: VoteQuestion - Allowed: Moderators/VIPs
1 - Location: Exact - Action: Vote1 - Allowed: <blank = all>
2 - Location: Exact - Action: Vote2 - Allowed: <blank = all>
