# Formatear fecha en Swift

## 1 - Si tengo un datePicker

```swift

    let dateFormatter = DateFormatter()
    dateFormatter.timeStyle = .short
    
    let strDate:String = dateFormatter.string(from: UIDatePicker.date)
    
```
