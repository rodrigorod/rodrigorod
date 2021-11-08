```php
<?php

namespace RodrigoCarracoRodrigues;

class About extends Me
{
    public function getAge(): int 
    {
        return 17;
    }

    public function getHobbies(): array
    {
        return [
            'hobbies' => [
                'cars' => ['f1', 'japanese cars (mazda mx-5 enthusiast)'],
                'video-games' => ['asseto-corsa', 'minecraft', 'apex', '...'],
                'drifting',
                'legos :)'
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
            HTML::class
            Php::class,
            Symfony::class,
            Laravel::class,
            Javascript::class,
            Vuejs::class,
            CSS::Class
            TailwindCss::class,
            Sass::class,
            MySQL::class,
            Java::class,
            Python::class,
            
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

