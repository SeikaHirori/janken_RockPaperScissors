

- Note #1 | Implementing various languages and how to obtain them
    - Various ways as suggested by users:
        - https://stackoverflow.com/questions/43428854/enum-identical-different-languages-classes
        - It's interesting to use a combo of enum and dictionary/HashMap together for scablility, as suggested by this answer:
            - https://stackoverflow.com/a/43431251
            - This seems to the be the most flexible as when adding additional languages, it can be it's own function/ enum.

- Note #2 | Example from Android
    - Checking locale device to see user's selected option, and have the app automatically switch the language to it.
        - https://stackoverflow.com/a/12954037
    - If the app doesn't have the a language in it's code, default to English