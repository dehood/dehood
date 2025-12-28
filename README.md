<h2 align="left"><img src="https://raw.githubusercontent.com/sidbelbase/sidbelbase/master/wave.gif" width="28px"><strong> Hello there, I'm Robert Račkauskas.</strong>
</h2>

[![Linkedin Badge](https://img.shields.io/badge/-Robert_Račkauskas-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/robertrackauskas/)](https://www.linkedin.com/in/robertrackauskas/)

<h3>A bit about me:</h3>

```php
<?php

namespace RobertRackauskas;

use World\Humans\Jobs;

class About extends Me
{
    use HasDigitalDesignerDiploma, LikesMotorcycles, LovesHomeAssistant, LinuxUser;

    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => null,
                'position' => 'Software Engineer',
                'job_type' => Jobs::CONTRACTOR
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Vuejs::class,
            TypeScript::class,
            JavaScript::class,
            //Angular::class,
        ];
    }
}
```

#### My GitHub stats:
![Robert's github stats](https://github-readme-stats.vercel.app/api?username=dehood&count_private=true&show_icons=true&theme=synthwave)

