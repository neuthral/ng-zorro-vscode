---
description:
  zh-CN: "下拉选择器"
  en-US: "Select"
---

```html
<nz-select [(ngModel)]="${1:value}" name="${1}" nzPlaceHolder="${2}"${3: nzAllowClear}>
  <nz-option
    *ngFor="let ${5:item} of ${4:list}"
    [nzLabel]="$5.label"
    [nzValue]="$5.value"
    [nzDisabled]="$5.disabled">
  </nz-option>
</nz-select>
$0
```
