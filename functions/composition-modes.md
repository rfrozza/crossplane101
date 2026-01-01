# Composition Modes Comparison

## Resources Mode (Traditional)
- Uses `resources:` field in composition
- Direct patch & transform operations
- Limited conditional logic
- Good for simple, static resource creation

## Pipeline Mode (Functions)
- Uses `pipeline:` field in composition  
- Functions process requests in sequence
- Advanced conditional logic with Go templates
- Complex transformations and calculations
- Better for dynamic, conditional resource creation

## When to Use Each

### Use Resources Mode When:
- Simple 1:1 claim to resource mapping
- No conditional logic needed
- Static transformations only

### Use Pipeline Mode When:
- Conditional resource creation (if/then logic)
- Dynamic resource generation (loops, arrays)
- Complex calculations or transformations
- Need advanced platform abstractions

### URLs
- https://github.com/crossplane-contrib/function-go-templating
- https://github.com/crossplane-contrib/function-auto-ready
- https://github.com/crossplane-contrib/function-patch-and-transform
