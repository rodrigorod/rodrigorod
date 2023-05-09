```php
<?php

namespace Rodrigo\Carraco\Rodrigues;

class About extends Me
{
    public function getAge(): int 
    {
        return 19;
    }
    
    public function getMedias(): array
    {
        return [
            'linkedin' => 'https://www.linkedin.com/in/rodrigo-carraco-rodrigues-310485247/'
        ]
    }

    public function getHobbies(): array
    {
        return [
            'hobbies' => [
                'cars' => ['f1', 'japanese cars (mazda mx-5 enthusiast)', 'drifting', 'WRC'],
                'music',
            ]
        ];
    }

    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Liip',
                'position' => 'Apprentice'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            'frontend' => [
                Javascript::class,
                Vuejs::class,
                NuxtJS::class,
                ThreeJS::class,
                TailwindCss::class,
                Sass::class,
                Twig::class,
                Blade::class
            ],
            
            'backend' => [
                PHP::class,
                Symfony::class,
                Django::class,
                Laravel::class,
                MySQL::class,
                ApiDevelopment::class
            ],

            'other' => [
                Java::class,
                Python::class,
                Firebase::class,
                Supabase::class,
                GitlabCI::class,
                Docker::class,
                MongoDB::class
            ]          
        ];
    }

    public function getFutureGoal(): array
    {
        return [
            'goals' => [
                'Contribute to open source',
                'Being a backend expert (Symfony, PHP, ...)'         
            ]
        ];
    }
}
```

