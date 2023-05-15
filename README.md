# CV

This is a tool I use to:
- author my CV and resume in Markdown,
- convert it to HTML,
- style it with some rough CSS,
- and finally convert it to pdf

## Notes

- This is not a polished tool. It's only made for me. The setup really doesn't make sense.
- This will probably only work in a Mac.
- `data/gfm.css` is a gfm-like style for rendering Markdown to HTML, which I've modified slightly to fit to my taste.

## Instructions for my future self

1. Install necessary tools

```bash
brew install pandoc
brew install weasyprint
```

2. Work on CV / resume

3. Check rendered pdf

```bash
yarn build:cv; yarn open:cv 
yarn build:resume; yarn open:resume
```

4. Rinse and repeat

## TODO

- [ ] Polish up CV
- [ ] Better (smarter)... formatting?
- [ ] Watch mode
- [ ] Github Actions to render, upload to personalweb
- [ ] Ability to author multiple versions of resume