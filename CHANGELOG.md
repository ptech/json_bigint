## 3.2.0
- Support `petitparser` 7, which needs Dart 3.8: `GrammarDefinition.build()` lost its type argument and `flatten()` takes the message as `message:`.
- Parse errors keep the same message and position; `ParserException.toString()` now reads `ParserException[line:column]: message`.

## 3.0.0
- Replace `useIntWhenPossible` with `whetherUseInt` in `DecoderSettings`

## 2.0.0
- Added `DecoderSettings` param to decode method.
- Renamed `encoderSettings` param to `settings` in encode method.

## 1.0.0+1
- Update README.

## 1.0.0
- Initial version.
