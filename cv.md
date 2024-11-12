## Matenova Meruert

1. **Personal Information:**

- Citizenship: Republic of Kazakhstan
- Date of birth: February 14, 2003 (21 years old)
- Gender: Female
- Marital status: Single
---

2. **Contacts:**

- Phone: +77026321254
- E-mail: meruert.matenova@mail.ru
- Telegram: @SadMoonshine
---

3. **Education:**

> Satbayev University: currently studying (4th year)
- Faculty: Cybersecurity, processing and storage of information
- Specialty: Information security
- Date of graduation: 2025
---

4. **Courses:**

- «Introduction to Cybersecurity» on Cisco Networking Academy (1 month)
- «Penetration Testing, Incident Response and Forensics» on Coursera (IBM university) (1 month)
- «Cyber ​​Threat Intelligence» on Coursera (IBM university) (1 month)
- «Cybersecurity Capstone: Breach Response Case Studies» on Coursera (IBM university) (1 month)
---

5. **Skills and Proficiency:**

- Basics of system administration
- Skills in working with Linux systems
- MSSQL, PL/SQL Database Administration
- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code, IntelliJ IDEA
---

6. **Code Example:**

Numbers API outputs a random fact about the number you enter into the string:

```
 const apiUrlFact = 'http://numbersapi.com';

    document.getElementById('get-fact').addEventListener('click', async () => {
        const numberInput = document.getElementById('numberInput').value;

        if (!numberInput.trim()) {
            alert('Пожалуйста, введите число.');
            return;
        }

        const apiUrl = `${apiUrlFact}/${numberInput}/trivia`;

        try {
            const response = await fetch(apiUrl);
            const data = await response.text();

            if (response.ok) {
                document.getElementById('fact').textContent = data;
            } else {
                console.error('Ошибка при получении данных: ' + data);
            }
        } catch (error) {
            console.error('Произошла ошибка при обработке запроса:', error);
        }
    });
```
---

7. **Languages:**
- Russian: native
- Kazakh: elementary
- English: B1-B2 (according to EPAM English Test <https://campus.epam.kz/en>)
