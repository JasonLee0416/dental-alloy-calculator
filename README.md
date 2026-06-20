# Dental Alloy Weight Calculator

A small browser tool for estimating the dental casting alloy required from a
wax pattern's weight and the selected material's specific gravity.

This was an early exercise in turning domain knowledge from dental laboratory
work into a focused software utility.

## Why It Exists

Manual alloy estimates can lead to material shortage or unnecessary waste,
especially when working with expensive alloys. The calculator makes the
assumption explicit and repeatable:

```text
required alloy = wax weight × specific gravity × 1.10
```

The final multiplier includes a 10% allowance for the sprue and button.

## Supported Materials

- Gold alloy, Type III
- Cobalt-chromium alloy
- Nickel-chromium alloy
- Titanium

## Run Locally

No build step or dependency installation is required.

1. Clone or download the repository.
2. Open [`dental-calculator.html`](dental-calculator.html) in a browser.
3. Enter the wax weight and select an alloy.

## Scope

This is a compact domain utility, not a clinical or manufacturing validation
system. Material values should be checked against the alloy manufacturer's
specification before production use.

## What I Learned

- A useful product can begin with one domain-specific calculation.
- Assumptions should be visible instead of hidden in a workflow.
- Small tools benefit from the same clarity around scope and limitations as
  larger applications.

## License

[MIT](LICENSE)
