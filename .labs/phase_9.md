# Phase 9 - Error Handling

## ✅ Requirements
Gracefully handle invalid expressions (e.g., malformed input, division by zero).

## ➕ Operators
All previous

## 🔬 Test Cases
- `assert_raises(SyntaxError, lambda: calculate("2++2"))`
- `assert_raises(ZeroDivisionError, lambda: calculate("10/0"))`
- `assert_raises(ValueError, lambda: calculate("abc"))`
