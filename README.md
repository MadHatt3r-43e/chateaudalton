# chateaudalton
Website for Eric Strickland Development and Engineering.  


## Message to TikTokker SwiftieExcel.  


Hi,

My name is Eric.  TikTok affords minimal space to properly communicate when a message-channel isn't accepted mutually.  This is my eleborated introduction and forthcoming 'collaboration' request.  

I'm an in-between-jobs software engineer/data engineer.   I live in Spokane, WA with daughter and granddaughters.  When the Eras tour began and people started posting concert snippets on TikTok, my journey to Swiftiedom began.  Bought Midnights, and was pleasantly surprised.  Red TV, Fearless TV, and reputation were next.  Anticipated and bought Speak Now TV on announcement day.  folklore and evermore followed, then 1989 TV, and of course The Tortured Poets Department.  Like "everyone", I'm ready to retire clowing and get repution TV.  :D  

I'm beginning to create a portfolio of applications and data applications which will reside on my website (Not this github page.)  Case study and blog articles for professional development blogs will be created, and likely also shared on LinkedIn.  

Regarding data, your data set chronicling the Eras tour is very impressive.  I was wondering if I could have / collaborate a copy of your MS Excel spreadsheet?  

*What would I do with it?*  

I would create data processing jobs to read the Excel worksheets and transform them into relationally-modeled data.  This data would then serve as source for a data application (a fancy viewer) using Observable Framework to visualize costuming by era, Suprise Songs, etc.  All data would be filterable and searchable.  The application would be distributable by simply placing a folder on your desktop or wherever.  You would have the deliverable application as well. 



This data application would be free to use and would carry branding in it's Help | About section bibliographically citing your data, tiktok address and whatever cross-promotion desired.  

Please, let's continue dialog via email if interested.   

-- Regards,
Eric  
estrickland70@outlook.com  

Linked In profile:  
https://www.linkedin.com/in/eric-strickland-b5b8725/  

Observable Notebook:  
https://observablehq.com/d/ab172da8afb854f9


#  










## Swiftie Data.  *(my current Swiftie data collection which is yours to download desired)*.  

This collection of Swiftie data was transformed, cleaned, and indexed from data source originating on Kaggle.  
        https://www.kaggle.com/datasets/ishikajohari/taylor-swift-all-lyrics-30-albums  




The transformed data has been placed on my Github profile here:  
        https://github.com/MadHatt3r-43e/chateaudalton/tree/main/SwiftieData/LyricsData  



### Lyrics Data.  

*albums.csv*  

**Primary Key** AlbumID added.  

Contains a record for each Taylor Swift album included in this dataset.  
- All 'BigMachine' albums.  
- All currently released "Taylor's Versions" *(as of 09.18.2024)*  
- Republic Studio 'fundamental' albums.  
- column representing album art filename found in AlbumArt folder.  

- NOT included:  The plethora of alt-releases, alt-packaging


*songs.csv*  

**Primary Key** songID added.  
ForeignKey: AlbumID.  


*lyrics.txt*  
Lyrics are contained one song line per record.  A song amounts to a set of lyrics records ordered ascending by [Lyric Line Number]  

**Primary Key** LyricId added.
SongId	
LyricId  
Lyric Line Number  
Lyric  


AlbumID -> songID -> LyricId.   


