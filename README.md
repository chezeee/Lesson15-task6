### task. **User <> Admin**

Необходимо отрефакторить класс `Admin`, чтобы он принимал четвертый параметр с
именем `userType`.
Например, `const admin = new Admin("Alex", "Blue", 20, "admin")`.

Метод `getFullName()` захардкоден, т.к. в конце всегда возвращает строку
`[admin]`. Вместо этого вам необходимо вернуть тип пользователя, полученного из
параметра.
