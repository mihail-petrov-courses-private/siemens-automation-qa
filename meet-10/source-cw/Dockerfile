# Избираме си официален IMAGE  от който да стартираме
FROM cypress/included:12.11.0

# Тук се изпълнява основния процес 
# Това е директорията на Docker инсталираната операционна система
WORKDIR /app

# Как да прехвърлим програмните файлове към Docker контейнера
COPY . .

# Да актуализираме всички текущи пакети
RUN npm install 

# Стартираме нашия Cypress скрипт
CMD ["npm", "run", "npx cypress run"]