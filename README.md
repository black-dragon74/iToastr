# iToastr
A custom swift extension used to show toast messages on iOS. 

# Usage
Download and copy Toast.swift to your project.

Show toast (inline) as
```swift
  Toast(with: "Your message").show(on: UIView)
```
or
```swift
  Toast(with: "Your message", color: UIColor).show(on: UIView)
```

You can also have a single instance and use it to show messages. Like:
```swift
  // Init the class
  let toastr = Toast(with: "Your message")
  
  // Now once view has loaded you may access message and color as objects like,
  toastr.message = "Hello there!"
  toastr.color = .green
  
  // And when you have to show the toast:
  toastr.show(on: UIView)
```

# Credits
Me :)

***Another opensource project by Nick ;=)***
