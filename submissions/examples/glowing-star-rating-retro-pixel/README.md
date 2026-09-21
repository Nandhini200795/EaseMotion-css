
# Glowing Star Rating — Retro Pixel

A pure CSS retro-pixel star rating component with glowing hover and selected states.

## Branch

```text
feat/glowing-star-rating-retro-pixel
```

## Files

- `demo.html` — Accessible component demo
- `style.css` — Component styles and responsive behavior

## Features

- Pure HTML and CSS
- Zero JavaScript dependencies
- Retro pixel-inspired visual style
- Glowing hover and selected states
- Keyboard focus visibility
- Responsive sizing for mobile, tablet, and desktop
- `prefers-reduced-motion` support
- CSS custom properties for motion and design tokens

## Usage

Open `demo.html` in a browser.

The rating uses native radio inputs, so users can select a rating with a mouse, keyboard, or assistive technology.

## EaseMotion Token Integration

The demo defines fallback custom properties such as:

```css
--ease-motion-fast
--ease-motion-normal
--ease-motion-spring
```

Map these to the repository's official EaseMotion tokens if equivalent tokens already exist.

Avoid introducing duplicate token names in the main component library.

## Accessibility

- Native radio controls provide semantic selection behavior.
- Each star has an accessible label.
- `:focus-visible` provides a visible keyboard focus indicator.
- `prefers-reduced-motion: reduce` minimizes animation and transitions.
- Color is not the only interaction mechanism.
- The controls remain keyboard navigable.

## Verification Checklist

Before opening the pull request:

- [ ] Run the repository's formatter and linter.
- [ ] Run the repository's accessibility checks.
- [ ] Test keyboard navigation.
- [ ] Test with reduced motion enabled.
- [ ] Verify mobile layout.
- [ ] Verify tablet layout.
- [ ] Verify desktop layout.
- [ ] Check Chrome.
- [ ] Check Firefox.
- [ ] Check Safari.
- [ ] Check Edge.
- [ ] Confirm official EaseMotion design tokens are used.

## Pull Request

### Title

feat: add glowing retro pixel star rating

### Description

#### Summary

Adds a responsive, pure CSS glowing star rating component with retro pixel styling.

#### Changes

- Adds accessible native radio-based star selection.
- Adds glowing hover and selected states.
- Adds responsive sizing and layout.
- Adds keyboard focus styles.
- Adds reduced-motion support.
- Documents token integration and verification steps.

#### Testing

- [ ] Manual browser testing
- [ ] Accessibility checks
- [ ] Reduced-motion testing
- [ ] Responsive layout testing
- [ ] Cross-browser verification

#### Screenshots

Add screenshots or a short screen recording before submitting the pull request.
