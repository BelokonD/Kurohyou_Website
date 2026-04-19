<h3> Таблиці до сайту </h3> <br />

**Таблиця "game_chapters":** <br />
chapter_id: int A.I, <br />
chapter_number: int, <br />
chapter_title: varchar, <br />
game_id: int <br />
<br />
**Таблиця "game_character":** <br />
character_id: int A.I, <br />
name: varchar, <br />
description: text, <br />
game_id: int, <br />
association: varchar, <br />
char_type: varchar, <br />
photo: longblob <br />
<br />
**Таблиця "game_info":** <br />
game_id: int A.I, <br />
title: varchar, <br />
genre: varchar, <br />
publish_date: date, <br />
platforms: varchar, <br />
countries: varchar, <br />
developer: varchar, <br />
publisher: varchar <br />
