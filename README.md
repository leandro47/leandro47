```php
<?php

namespace Dev;

class About extends Me
{
    protected function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'SoftExpert',
                'position' => 'Software enginner'         
            ]
        ];
    }

    protected function getKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            CodeIgniter::class,
            Vuejs::class,
            Bootstrap::class,
            Materialize::class,
            Api::class,
            SqlServer:class,
            PostgreSQL::class,
            Mysql::class,
            Oracle::class,
            Firebase::class,
            Git::class,
            Jira::class,
            Gitlab::class,
            Bitbucket::class,
            Trello::class
        ];
    }

    protected function getContact(): array
    {
        return [
           'linkedin' => 'https://www.linkedin.com/in/leandro-silva-a5b84318b/',
           'email' => 'leandrosilva47@live.com',
           'webSite' => 'https://leandro47.com/'
        ]
    }
}
```
