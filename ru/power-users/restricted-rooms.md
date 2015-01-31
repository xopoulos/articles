***
В данной статье подробно рассматривается вопрос о правах доступа к информации внутри мессенджера Kato.

Пользователи могут приглашать внешних людей в специальные приватные комнаты внутри команды, а администраторы могут создавать комнаты, которые увидят только конкретные члены команды. Комнаты, которые видят все члены команды называются «публичными».

По умолчанию все вновь создаваемые комнаты являются публичными, и каждый вновь приглашенный член команды получает доступ ко всем публичным комнатам.

### Пример #1
HR-специалст компании назначил собеседование с разработчиком по имени Петя. В ходе интервью будут затронуты и технические темы, поэтому необходимо участие двух уже работающих в компании разработчиков.

В данном случае HR-специалист создат комнату в Kato под названием «Собеседование Пети» и пригласит туда, собственно, Петю и двух других разработчиков. После завершения интервью HR-специалист может исключить из комнаты Петю, при этом в ней останется вся история сообщений, которую можно использовать для принятия решения о приеме кандидата на работу.

### Пример #2
Компания «Супер Технологии» привлекла инвестиции в ходе раунда А и планирует потратить часть из них на найм большого количества новых сотрудников. Организации понадобится HR-специалист, который должен иметь выделенный канал связи с основателями и другими руководителями компании.

В такой ситуации хорошим выходом будет создание комнаты под названием «HR», доступ к которой имеют все заинтересованные стороны. Эта комната станет защищенным каналом связи, в котором будут происходить обсуждения вопросов, связанных с поиском и приглашением новых сотрудников.

### Создание приватных комнат

Администратор команды Kato при создании новой комнаты могут присвоеть ей статус «приватной» и выбрать пользователей, которые получат к ней доступ:

![clip.png](https://s3.amazonaws.com/kato-share/5b5fb4b325ef5920c209f40fefcbc6dc79622613e0314148bc98f99c7730114/clip.png)

### Приглашение пользователей в приватные комнаты
В Kato существует возможность не просто пригласить нового пользователя, но и указать список комнат, к которым он получит доступ:

![clip.png](https://s3.amazonaws.com/kato-share/130484a68d83584df8f0d269a648ee0f14d1091cc12ac129419bcba455f695a/clip.png)

### Приглашение пользователей с доступом ко всем публичным комнатам
Если в процессе приглашения пользователя выбрать флаг **[All Unrestricted Rooms]**, то новый член команды получит доступ ко всех публичным комнатам (также можно выдать ему доступ к конкретным приватным комнатам):

![clip.png](https://s3.amazonaws.com/kato-share/19886620805031b8d56e1e148474b24097762d3742a4e01ce65fc4fdb5939a30/clip.png)

Если в процессе отправке приглашения новому пользователю не указать комнат, к которым он должен получить доступ, то такой член комнады сможет общаться только с администраторами в режиме 1-1.

### Иконка зонтика

Приватные комнаты помечены иконкой зонтика: ![clip.png](https://s3.amazonaws.com/kato-share/e00d5b0d88b2357867eaa1956bc7344624602bdc866ddab93471de9e5b4caa2f/clip.png)

### <a href="#access" name="access">У кого есть доступ к комнатам</a>
Администраторы команды Kato могут создавать приватные комнаты и выдавать права доступа к ним другим пользователям. ** Чтобы увидеть историю сообщений администратору нужно выдать права на доступ к комнате самому себе. **

Все изменения прав доступа к приватным комнатам фиксируются в комнате [журнала проверок безопасности](/articles/ru/power-users/security-audit-log/) (если такие журналы включены).

Имена всех членов команды, имеющих доступ к приватной комнате, появятся в верхней части ростера — они будут помечены красной чертой справа.

![clip.png](https://s3.amazonaws.com/kato-share/7a7e61188b15aafda81ca88a9d63210e4662cdd15040d5e1624cfa8610ab372/clip.png)

### Кто кого видит
Все члены команд с доступом ко всем публичным комнатам будут видеть друг друга и разговаривать друг с другом в комнатах 1-1 (если такие комнаты не запрещены администраторами в настройках конкретной команды).

Пользователи, обладащие доступом только к приватным комнатам будут видеть в ростере пользователей, у которых есть такие же права, а также администраторов команды.

Пользователи, имеющие доступ к различным приватным комнатам в рамках одной команды не будут видеть друг друга в своих контакт-листах.

## <a href='#changing-room-access-type' name='changing-room-access-type'>Изменение типа комнаты</a>
Для изменения статуса комнаты с публичного на приватный и наоборот администратору команды нужно зайти настройки комнаты и перейти во вкладку **Access**. Для завершения процесса потребуется ввести пароль администратора:

![clip.png](https://s3.amazonaws.com/kato-share/cc0631502f34a1f68797e9b74e60276b782edeba61481086f5caa49a42a92c7c/clip.png)

**Примечание*: изменение статуса комнаты с приватного на публичный безвозвратно уничтожит список пользователей, ранее имевших доступ к этой комнате.