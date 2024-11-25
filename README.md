Flutter package that makes text more readable.<br>
It works with fixed-width as well as variable-width fonts.

![text balancer demo](https://github.com/user-attachments/assets/e58b0433-f315-4168-be77-980fa9e00a10)

## How To Use
```dart
/// Widget
TextBalancer('text');

/// Text Extension
Text('text').balance(
  context,
  maxWidth: constraints.maxWidth,
);

/// String Extension
'text'.balance(
  textStyle: textStyle,
  maxWidth: constrains.maxWidth,
)
```

## Performance
![performance](https://github.com/user-attachments/assets/9c5890c8-40cc-491b-b535-f2cee4c41d80)

- Time complexity : `n^2`

## References
- https://xxyxyz.org/line-breaking
