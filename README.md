sqlite3 thiago.db
CREATE TABLE contatos (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    nome TEXT NOT NULL,
    telefone TEXT,
    email TEXT UNIQUE
);
.exit

Terminal

npm install express sqlite3
