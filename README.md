# MBTL-Community-Patch
A community translation patch for MBTL

Credits to Petrikow, Comun, Fumei and Lianru

## Editing guidelines

There are certain things that are standardized across the project.

### Technical limitations

The behavior of how the game interprets the files differs on the category of file.

#### Scripts & Win-quotes

The chatbox for the story-mode scripts and the win-quotes function the same.
The amount of characters possible to be parsed in a single line before overflowing is around 60-70 (the actual amount depends on difference in character width, hence the variability). Going over this amount will cause the text to clip outside the frame.
The chatbox supports 3 lines. However, the 3rd line needs to be shorter than the first 2. This is because otherwise it clips into the "click to read next" button. Try to keep it within 40-50 characters.

#### Command list (cmddef.ini)

The command list is fairly simple. There is however still a character limit to adhere to. An approximate character limit is around 40-45, but keeping under 40 is recommended.

#### Battle voices (stringfile_battlevoice.xml)

The file marks the beginning and start of the battle voice strings with commas, so in order to use commas in the middle of text, that text must first be wrapped in quote ("") marks.
The amount of characters supported by the battle voice format is remarkably long, easily over 100 characters. Realistically speaking, it should be able to contain most translations without any problems.

### General Conventions

Japanese names are currently all in western order.

No honorifics or other Japanese familiarity terms.

Spelling is generally American (Archetype Earth spells differently).

### Characterization

For individual characters.

#### Arcueid (000)
Casual speak. Cheerful, innnocent. Sometimes changes her tone when serious to be a bit less casual.

Calls everyone by their first name.

#### Hisui (001)
Very formal, uses polite expressions. However, her speech is otherwise brief and to the point. Sometimes has a dead-pan silly mode. 

Calls men "Mister x" and women "Miss x" (-様). Calls Shiki "Master Shiki", and Akiha "Lady Akiha".

#### Akiha (002)
Formal and uses polite expressions. Can be very eloquent. Can both show her hostility directly and indirectly. Sometimes liable to use sarcasm.

Calls people by their first name or title.

#### Shiki (003)
Casual speak. Direct and to the point, even more so when he's upset (glasses-off).

Calls people by their first name.

#### Kohaku (004)
Casual speak with polite expressions. Especially liable to speak casually to Hisui. Can be quite silly. 

Calls Akiha "Lady Akiha", but refers to Shiki by his first name. Refers to most other people by their first name.

#### Roa (005)
Speaks fairly neutrally. Has a very technical and expansive vocabulary. Excudes a lot of smugness, and will take to creative means in order to rile people up.

Calls people by their last-name, or titles.

#### Kouma (006)
Has a curt and stiff way of speaking. Doesn't show much emotion. Uses a lot of Buddhist terminology, rendered from Japanese to their Indian equivalent.

Usually calls people by monikers.

#### Maids (007)

See Hisui and Kohaku

#### Noel (008)
Has a very casual register, unless she's trying to suck up to people. Uses youthful slang, despite being in her late 20s.

Calls people by their first name. Calls Mario "Acting Presbyter" (his rank). Calls non-humans without using their name, calling Arcueid "that True Ancestor" and the like.

#### Vlov (009)
Has a formal yet direct way of speaking. His speech is drawling and slow, which is often represent by ... being interspersed in his sentences (just 、in Japanese). 

Refers to people by monikers. Refers to Zaria (his vampire sire) as "my liege" (ご当主様). Refers to Roa as "vile Serpent" (蛇め). 

#### Warc (010)
Very close to Arcueid, but more emotional and worked up.

#### Ciel (011)
Speaks fairly neutrally. Changes her tone a lot depending on who she's talking to. Is friendly and approachable to humans, but cold and curt towards non-humans. Doesn't know which one of these to use against Arcueid (unless its Warc, in which case she's more cold)

Calls people by their first names. Calls Shiki "Tohno" (遠野君) instead. Calls Mario by his rank, "Acting Presbyter" (司祭代行).

#### Saber (012)
Speaks very formally and to the point. Has a regal bearing.

Calls people by monikers.

#### Miyako (013)
Speaks childishly and with a poor vocabularly. Uses cliche Kung-Fu phrases. 

Calls people by their first name. Refers to her panda-trainer as "Master".

#### DA Noel (014)
Speaks casually and slightly crudely. Will refer to herself in aggrandizing terms, and others in demeaning terms. 

Calls people by their first name.

#### Aoko (015)
Speaks casually and light-heartedly. Has a jovial yet straight-forward tone. 

Calls people by their titles or first names.

#### P. Ciel (016)
Has a very stiff and formal way of speaking. Will use mission-briefing style speech-patterns ("Target confirmed. Commencing attack", etc).

Calls people by their titles or last names.

#### Mario (017)
Has an incredibly rude way of speaking. Swears a lot. His speech is full of vulgar expressions. Uses shortened speech (gotta, aboutta, 'lil, 'a (instead of "of") 'em (instead of "them"), etc) Sometimes speaks more normally when he's thinking or reminiscing.

Calls people by demeaning nicknames. Calls Noel "fatass" (ﾌﾞﾀ). Calls Arcueid "the True Ancestor Princess" (神祖の姫).

#### Archetype:EARTH (0??)
Speaks in archaic English. Uses antiquated grammatical expressions (second-person inflections on verbs) alongside old pronouns.

### Terminology

For words that appear repeatedly and need to be kept consistent

In general, terminology is left uncapitalized unless it intersects with another meaning of the word. 

For example: Executor (an agent of the Holy Church) as a term is kept capitalized as to differentiate it from executor (someone who executes people) as a word. Like wise a Dead Apostle (type of vampire) is not just a dead apostle (an apostle that is dead).
In contrast, magecraft only ever refers to the term, and as such is not liable to be misconstrued as anything else.

In addition, some things are capitalized by virtue of being names of organizations, places or titles.

| Japanese    | English                 | Explanation             |
| :---------- |:----------------------- |:-----------------------
| 原理　　　　　　　 | Principle               | Ability gained by vampires that live long.
| 原理血戒　　　 　| Idea Blood              | Ability possessed by the 27 Ancestors.
| 使徒　　　　　　 　| Dead Apostle            | Common type of vampire.
| 二十七祖　　　 　| 27 Ancestor(s)          | Most powerful type of Dead Apostle.
| 真祖　　　　　　 　| True Ancestor           | Rare type of vampire.
| 吸血種　　 　 　　| bloodsucker             | Any species that sucks blood.
| 吸血鬼　　　　  　| vampire                 | Type of bloodsucker (includes DA and TA)
| 吸血衝動　　　　　| vampiric urges          | Urge to suck blood. Strong among TAs.
| 魔術　　　　　　　 | magecraft               | Ability to reproduce Mystery.
| 魔術回路　　　　　| magic circuits          | Organ used for magecraft.
| 魔術師　　　　  　| mage(s)                 | People who use magecraft.
| 魔術教会　　　 　| (the) Mages Association | Organization that practices magecraft.
| 神秘　　　　　 　　| Mystery                 | Supernatural phenomena.
| 魔法　　　　　 　　| magic                   | Peak of magecraft. There are only 5.
| 魔法使い　　　 　| magician                 | Someone who can use magic.
| 魔力　　　　　 　　| magical energy          | Energy used for all kinds of Mystery.
| 魔眼　　　　　 　　| Mystic Eyes             | Supernatural eyes.
| 直死の魔眼　 　　| Mystic Eyes of Death Perception| Shiki's Mystic Eyes.
| 死者　　　　　　　　| the Dead (p)/Dead(s)    | Undead familiars created by Dead Apostles.
| 聖堂教会　　 　　| (the) Holy Church       | Organization dedicated to killing vampires
| 代行者　　　　 　| Executor                 | Church agent who kills vampires.
| 埋葬機関　　　 　| Burial Agency           | Special unit within the Church.
| 司祭　　　　　　 　| Presbyter               | Rank within the Church.
| 司祭代行　　　 　| Acting Presbyter        | Mario's title.
| 人形使い　　 　　| Puppetmaster            | Mario's first nickname.
| 人間使い　　 　　| Peoplemaster            | Mario's second nickname.
| 混血　　　　　 　　| Mixblood                | Human who has intermixed with non-humans
| 鬼　　　　　 　 　 | oni                     | Type of Japanese non-human.
| 独角         | Lone-Horn               | Kouma Kishima's martial art style.
| 北海         | northern seas           | Where Vlov comes from. Not the North Sea.
| 星の内海      | (the) planet's inner-sea| Reverse side of Earth.
| チャイナ       | China-girl              | Neko-Arc's nickname for Miyako
| メガネ        | glasses-boy             | Neko-Arc's nickname for Shiki
| 親(元)       | Sire                    | Vampire 'parent'. Only for vampires.
| 子　　　　　　　　　　| Scion                   | Vampire 'child'. Only for vampires.
| 七つの死因     | Seven Causes of Death   | The concept of the Seventh Holy Scripture.

## Progress

### Scripts

| Character       | Status                           | 
| :-------------- |:-------------------------------- | 
| Arcueid   (000) | Play-testing adjustments (Petri) |
| Hisui     (001) | Play-testing adjustments (Petri) |
| Akiha     (002) | Play-testing adjustments (Petri) |
| Shiki     (003) | Play-testing adjustments (Petri) |
| Kohaku    (004) | Play-testing adjustments (Petri) |
| Roa       (005) | Play-testing adjustments (Petri) |
| Kouma     (006) | Play-testing adjustments (Petri) |
| Maids     (007) | Play-testing adjustments (Petri) |
| Noel      (008) | Play-testing adjustments (Petri) |
| Vlov      (009) | Play-testing adjustments (Petri) |
| Warc      (010) | Play-testing adjustments (Petri) |
| Ciel      (011) | Play-testing adjustments (Petri) |
| Saber     (012) | Play-testing adjustments (Petri) |
| Miyako    (013) | Play-testing adjustments (Petri) | 
| Boss Rush (013) | Play-testing adjustments (Petri) |
| DA Noel   (014) | Play-testing adjustments (Petri) |
| Aoko      (015) | Play-testing adjustments (Petri) |
| P. Ciel   (016) | Play-testing adjustments (Petri) |
| Mario     (017) | Play-testing adjustments (Petri) |

### Win-quotes

| Character       | Status                         | 
| :-------------- |:------------------------------ | 
| Arcueid   (000) | Play-testing adjustments (Petri) |
| Hisui     (001) | Play-testing adjustments (Petri) |
| Akiha     (002) | Play-testing adjustments (Petri) |
| Shiki     (003) | Play-testing adjustments (Petri) |
| Kohaku    (004) | Play-testing adjustments (Petri) |
| Roa       (005) | Play-testing adjustments (Petri) |
| Kouma     (006) | Play-testing adjustments (Petri) |
| Maids     (007) | Play-testing adjustments (Petri) |
| Noel      (008) | Play-testing adjustments (Petri) |
| Vlov      (009) | Play-testing adjustments (Petri) |
| Warc      (010) | Play-testing adjustments (Petri) |
| Ciel      (011) | Play-testing adjustments (Petri) |
| Saber     (012) | Play-testing adjustments (Petri) |
| Miyako    (013) | Play-testing adjustments (Petri) | 
| DA Noel   (014) | Play-testing adjustments (Petri) |
| Aoko      (015) | Play-testing adjustments (Petri) |
| P. Ciel   (016) | Play-testing adjustments (Petri) |
| Mario     (017) | Play-testing adjustments (Petri) |

### Strings

| Subset                                   | Status                       |
| :--------------------------------------- | :--------------------------- |
| Command List (cmddef.ini)                | Finalized (Petri)            |
| Battlevoice (stringfile_battlevoice.csv) | Arcueid lines edited (Petri) |