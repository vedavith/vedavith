
```php
<?php
namespace VedavithRavula;
class ProfessionalInsight extends AboutMe
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Genpact',
                'position' => 'Lead Consultant'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            AspDotNet::class
            Javascript::class,
            Laravel::class,
            Symfony::class,
            React::class,
            Flutter::class,
            EntityFramework::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
