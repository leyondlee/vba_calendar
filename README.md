<div align="center">
  <img src="images/image1.jpg">
</div>

# VBA_DatePicker
VBA_DatePicker is a datepicker form written in VBA. It was developed for developers to provide a way for users to select a date from a calendar.

## Setting up
1. Open your project in **Microsoft Visual Basic for Applications**.
2. Import the following files: (`File` > `Import File`)
   - `DatePickerDayLabel.cls`
   - `DatePickerMod.bas`
   - `FormDatePicker.frm`

## Usage
```
Dim result as Variant
result = DatePickerMod.selectDate()
```
