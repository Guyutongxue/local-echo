## Changelog

## 0.1.8
*2023.9.30*
- Fix: Add a newline before prompt when prompt is explicit set.

## 0.1.7
*2022.1.15*
- Fix: cursor position mismatch when input is called frequently.

## 0.1.6
*2022.1.14*
- Fix: correctly parse pasted multiline input.

## 0.1.5
*2022.1.14*
- Fix: waiting for current write when a read is requested.

## 0.1.4
*2022.1.12*

- Feature: Listen on Ctrl-C or Ctrl-D by `onInterrupt` or `onEof`.
- When entering Ctrl-D, abort pending read operation.

## 0.1.3
*2022.1.5*

- Feature: when no prompt is providing, use the part of the current line that has been printed as the prompt.
- Fix: write should be async function.

## 0.1.2, 0.1.1
*2021.10.31*

- Bugfix: remove extra newline when no prompt is given.

## 0.1.0
*2021.10.31*

- Add CJK support.
- Add Tab support.
- Add more options: 
    - Choose to show auto-completion or not;
    - Choose to enable incomplete-input-continuation or not.

