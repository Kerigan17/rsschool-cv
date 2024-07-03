## Alexandr Malko


### Contacts
- **Phone:** +375336676888
- **Email:** aleksandr.malko.98@mail.ru
- **Telegram:** [alex_malko_17](https://t.me/alex_malko_17)
- **GitHub:** [Kerigan17](https://github.com/Kerigan17?tab=repositories)


### About me
Hello! My name is Alexander. I work in education, but want to move into development. 
I am constantly improving my skills as a front-end developer


### Education and Additional Courses
- **Belarusian State Pedagogical University named after Maxim Tank**
  - Major: Physics and Computer Science
- Curses **ITlogia**
  - frontend-developer


### Skills and Experience
- **Programming Languages:** HTML, CSS, JavaScript, TypeScript, jQuery, Regex
- **Development Tools:** Gulp, Grunt, Git
- **Frameworks:** SPA, Angular, React


### Code example
```
private async createNewCategory(value: string): Promise<void> {
    try {
        await CustomHttp.request(config.host + '/categories/' + this.page, 'POST', {
            title: value
        });
        location.href = '#/' + this.page;
    } catch (error) {
        console.log(error);
    }
}
```

