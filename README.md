```swift
//
//  readmeApp.swift
//  SoftwareEngineer
//
//  Created by teeshkeen on 21.07.2024.
//

struct SoftwareEngineer {
    let fullName: String
    let age: Int
    let level: String
    let languageSpoken: [String]
    
    private func sayIt() {
      print("Sometimes life hits you in the head with a brick. Don’t lose faith.")
  }
}

let me = SoftwareEngineer(
    fullName: "Alexey Tishkin",
    age: 20,
    level: "Junior/Middle"
    languageSpoken: ["en_US", "ru_RU"]
)
 
me.sayIt()
```
