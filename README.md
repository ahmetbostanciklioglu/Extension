# Extensions




**Extensions:**

extension Double {

    //Stored values can't be used in extensions, and therefore use computed values
    var pi: Double {
        return 3.14
    }
    
    //Function in extension
    func AreaOfCircle() -> Double {
        return 2 * pi * self
    }
}

let radius : Double = 2
print("Area of circle is \(String(format: "%.2f", radius.AreaOfCircle()))")



