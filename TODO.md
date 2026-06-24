# TODO

- [x] Update `assets/global.js`:
  - [x] Add null-safety in `VariantSelects.toggleAddButton()` for missing elements (`loading-overlay__spinner`, `product-form__buttons-icon`, price nodes).
  - [x] Synchronize selected variant id to preorder/backorder add-to-cart elements by setting `[data-variant-id]` inside the relevant product forms/section when variant changes.
- [ ] Validate:
  - [ ] No more `Cannot read properties of null (reading 'innerHTML')` errors.
  - [ ] Changing variant updates URL and the add-to-cart adds correct selected variant.


