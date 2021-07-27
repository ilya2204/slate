# Span

A `Span` is a low-level way to refer to a range using `Element` as the end points instead of a `Point` which requires the use of leaf text nodes.

```typescript
type Span = [Path, Path]
```

- [Static methods](range.md#static-methods)
  - [Check methods](range.md#check-methods)

## Static Methods

### Check Methods

#### `Span.isSpan(value: any) => value is Span`

Check if a `value` implements the `Span` interface.