# open-static-for-demo

Static sample files served straight from GitHub for XOR demos.

## vendor-onboarding/

Placeholder documents for the "Autofill - Demo" button on `/vendor/onboarding`. One PDF per
file field in the vendor schema, so a demo run fills every upload slot without anyone having to
pick real paperwork off a laptop.

Every file is generated sample data. None of them is a real certificate, licence, or bank
record, and none carries any legal meaning.

Raw base URL:

```
https://raw.githubusercontent.com/sujal-tangde/open-static-for-demo/main/vendor-onboarding/
```

The frontend keeps the field-to-filename mapping in
`src/pages/Vendor/Onboarding/vendorDemoValues.data.ts`.
