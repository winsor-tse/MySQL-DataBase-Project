#Bot database
A company called WITS Inc is manufacturing bots used inside many web applications. It follows the
following business rules:
a. A bot type information should be recorded once it is created.
b. A bot developer information shall be recorded.
c. One developer can create many bots while one bot is created by only one developer.
d. A client is recorded when the client acquires a bot in service. The bot acquired is one of the types
on the bot type table.
e. Once a bot is adopted by a client. The client is termed as a master with respect to the bot. Master
and bot are bounded. The bot will be given a nickname and its service start date and end date are
recorded.
f. To be clear, one bot type can generate many bots with different names put into service.
g. A client can acquire many bots.
h. A social media application that allows its users (masters) to use bots is recorded, name and its bot
url as location are recorded. A user can register many bots. The users’ names are the same as
masters but can have different names. For example, M1 can be used by the WITS company to
identify its client while U1 can be used as a user in one social media application. M1 and U1 are
the same.
i. There are many social media applications, some of them allow bots to be used, some not.
Use MYSQL workbench (or any other tools) to design an
ER diagram. With the ER Diagram, students can create tables using the so called forward engineering
process. Once tables are created, students can enter data to tables. Each table shall have at least 10 entries
(so to make meaningful queries).
Once the database is in place, students are asked to make the following queries.
1. list bot type information sorted by its birthdate (creation date).
2. give the count of bots under each type created.
3. list those who adopt bots ordered by its service start date, and nickname.
4. list social media applications names who allow bots to be used, ordered by the number of bots in
its platform.
5. find out bot developers who are working in Dobbe Ferry in NY state.
The WITS Inc is thinking to expand its business and would like to have more features incorporated into
its database. Students are asked to make modification and addition to the existing business model. It is
open ended scenario to db design.
