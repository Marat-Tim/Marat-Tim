![NO AI](https://raw.githubusercontent.com/nuxy/no-ai-badge/master/badge.svg)
Page written without AI

<div align="center">
    <h1>Hi, I am Marat Tim 👋</h1>    
    <h3>22 yo programmer from Moscow</h3>
</div>
<div align="center">
    <a href="https://t.me/marattim123">
        <img src="https://img.shields.io/badge/telegram-cccccc?logo=telegram&style=for-the-badge" alt="telegram"/>
    </a> 
    <a href="https://vk.com/marat_tim1">
        <img src="https://img.shields.io/badge/vk-blue?logo=vk&style=for-the-badge" alt="vk"/>
    </a> 
    <a href="mailto:magatbaraev@gmail.com">
        <img src="https://img.shields.io/badge/gmail-red?logo=gmail&logoColor=white&style=for-the-badge" alt="gmail"/>
    </a> 
    <a href="https://instagram.com/marat_tim123?igshid=MmIzYWVlNDQ5Yg==">
        <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white" alt="vk"/>
    </a> 
</div>

👀 I am interested in:

- Java backend development
- Developer tools
- Writing beautiful code
- And any other programming (but the previous points I like the most)

🎓 I studied at the Higher School of Economics (HSE), Faculty of Computer Science, software engineering (4 years),
[my diploma](https://www.hse.ru/edu/vkr/1046846982)

🏭 Work experience

**11.2022 - 06.2024 (1y8m): teaching assistant**

- creating tasks
- checking HWs
- accepted exams

**03.2024 - 08.2026 (2y6m): intern to middle java backend in Raiffeisen Bank (digital lending for legal companies)**

- product development (solve tasks for business)
- work with openxml (for generating docx)
- migrating monolith to microservices (and writing own microservices on spring boot)
- integrations by rest, kafka, artemis (dadata, СМЭВ, CRM and internal systems)
- working with cucumber tests
- writing many spring boot starters (kerberos auth/client/kafka, logbook with masking, request id lib and others)
- migrating spring boot 2 → 3 → 4
- writing many gradle plugins (default openapi generators, union of errorprone + nullaway + checkerframework, default
  jib and others)
- writing many small automation scripts (find users in log, create AI reviewer in project, generate new project from
  template and others)

Example of my problems during development https://stackoverflow.com/users/22989572/marat-tim?tab=questions&sort=newest

🐸 Tech skills:

<div>
    <div>
        <img align="left" src="https://devicons.io/devicons/icons/openai-icon.svg" width="50px" alt="claude"/>
    </div>
    <div>
        <p>
            <strong>AI dev</strong> - I use opencode TUI. Most time I use chatgpt or internal qwen model.
            I understand opencode customization, write my own agents, skills and 
            <a href="https://github.com/Marat-Tim/MattermostSearchMCP">MCP for searching in mattermost messenger</a>.
        </p>
        <p>I used our own harness written in the team</p>
        <p>
            I don't like idea to write all code using agents. 
            I think main part of code is understanding and to achieve it, you need to write it yourself
        </p>
    </div>
</div>

<div>
    <div>
        <img align="left" src="https://devicons.io/devicons/icons/java.svg" width="50px" alt="java"/>
    </div>
    <div>
        <p><strong>Java</strong>(17-25) with Spring Boot(2-4) is my main lanuage</p>
        <p>I use Gradle and I can write plugins for it</p>
        <p>
            I works many with Spring Boot: Web(can write CRUD apps), Jpa(can write jpql, criteria queries), 
            Security(can configure many params of SecurityConfig, can write own filters)
        </p>
        <p>I works with: jooq, hibernate(six-seven), apache-*, docx4j, logbook, cucumber, etc</p>
        <p>
            At university we write
            <a href="https://arxiv.org/abs/2410.10425">
                scientific article about relationship between immutability and cyclomatic complexity
            </a>
        </p>
        <p>I can write plugins for intellij - <a href="https://github.com/Marat-Tim/VacuumJetbrainsPlugin">vacuum plugin</a></p>
        <p>I write <a href="https://github.com/Marat-Tim/HSE-HomeworkJava/blob/master/MyDI/src/test/java/ru/marat/DITest.java">my own DI container</a> for study</p>
    </div>
</div>

<div>
    <div>
        <img align="left" src="https://devicons.io/devicons/icons/postgresql.svg" width="50px" alt="postgresql"/>
    </div>
    <div>
        <p><strong>Postgresql</strong> - my main sql</p>
        <p>
            I work many with JSONB
            (for example I know different between <code>j->'field' IS NOT NULL AND j->'field' != 'null'::jsonb</code>
            or why we need prefer <code>j ? 'key'</code> to <code>jsonb_exists(j, 'key')</code> 
            and why first option will not work in native jpa query)
        </p>
        <p>I know pessimistic and optimistic locks, transactions levels</p>
        <p>I know why <code>WHERE column IS NULL OR column = :param</code> is bad idea</p>
    </div>
</div>

<div>
    <div>
        <img align="left" src="https://devicons.io/devicons/icons/openapi-icon.svg" width="50px" alt="openapi"/>
    </div>
    <div>
        <p><strong>Open API</strong> - I know it in context of API first</p>
        <p>
            I was first in company who automate 
            <a href="https://github.com/Marat-Tim/Raiffeisen-VacuumExtensions">linting openapi files</a>
            by company standards
        </p>
        <p>I contribute to <a href="https://github.com/daveshanley/vacuum/pulls?q=is%3Apr+author%3AMarat-Tim">vacuum openapi linter</a></p>
        <p>I create <a href="https://github.com/Marat-Tim/VacuumJetbrainsPlugin">Intellij IDEA plugin for vacuum</a></p>
        <p>I tried to <a href="https://github.com/Marat-Tim/Raiffeisen-ApiGuideLinterUsingLlm">lint openapis using LLM</a></p>
    </div>
</div>

✍️ In my free time, I like to listen to programming conferences (Jpoint/Joker, java rock stars, black hat and others),
writing small PRs to open source or develop personal projects
