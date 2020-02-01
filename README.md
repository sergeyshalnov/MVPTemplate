# MVP Template
It's a shared template for Generamba code generator.

## Prepare

Create file with `ModuleInterface` structure

```
struct ModuleInterface<ModuleInput> {
    
    let input: ModuleInput
    let view: UIViewController
    
}
```

## Usage

Add the following line to the Rambafile and have fun!

```
templates:
- {name: MVP, git: 'https://github.com/sergeyshalnov/MVPTemplate'}
```

