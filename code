import UIKit

let string: [Any]

func testForString(string: Any) -> Bool{
    var isString = string is String
    if isString == true {
        let decimalCharacters = CharacterSet.decimalDigits

        let range = (string as! String).rangeOfCharacter(from: decimalCharacters)

        if range != nil {
            isString = false
        }
    }
    return isString
}

testForString(string: "sdwdad")
