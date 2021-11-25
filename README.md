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
            'frontend' => [
                HTML::class
                CSS::Class
                Javascript::class,
                Vuejs::class,
                Vuex::class
                NuxtJS::class,
                ThreeJS::class,
                TailwindCss::class,
                Sass::class,
            ],
            
            'backend' => [
                PHP::class,
                Symfony::class,
                Django::class,
                Laravel::class,
                MySQL::class,
            ],

            'other' => [
                Java::class,
                Python::class,
                Firebase::class,
                Supabase::class,
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

