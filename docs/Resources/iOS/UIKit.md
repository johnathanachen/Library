# UIKit

## TableView Resources 
> Medium: “How to build a TableView with multiple cell types”  
> [iOS: How to build a Table View with multiple cell types](https://medium.com/@stasost/ios-how-to-build-a-table-view-with-multiple-cell-types-2df91a206429)  
>   
> StackOverFlow: “Multiple UITableViewCell types programmatically”  
> [Multiple UITableViewCell types programmatically](https://stackoverflow.com/questions/48346139/multiple-uitableviewcell-types-programmatically)  
>   
> StackOverFlow: “How to create UITableView programmatically in Swift”  
> [How to Create UITableView programmatically in Swift](https://stackoverflow.com/questions/40220905/create-uitableview-programatically-in-swift)  

## UIButton Resources
>  StackOverFlow: “Adding a closure as target to a UIButton”  
> [ios - Adding a closure as target to a UIButton - Stack Overflow](https://stackoverflow.com/questions/25919472/adding-a-closure-as-target-to-a-uibutton?noredirect=1&lq=1)  

## UITextField Resources 
> StackOverFlow: “Using a Textfield in Swift 3 for Search Instead of a Search Controller” [using a textfield for search ](https://discourse.algolia.com/t/tutorial-using-a-textfield-in-swift-3-for-search-instead-of-a-search-controller/1308)  

## UISlider Resources 
> StackOverFlow: “Event not triggering in UISlider programmatically created in Swift 3”  
> [ios - Event not triggering in UISlider programatically created in Swift 3 - Stack Overflow](https://stackoverflow.com/questions/42719060/event-not-triggering-in-uislider-programatically-created-in-swift-3)  


## UITextView Resources 
> StackOverFlow: “How to expand - collapse UITextView in Swift?”  
> [How to expand - collapse UITextView in Swift? ](https://stackoverflow.com/questions/40876158/how-to-expand-collapse-uitextview-in-swift)  

## Enumerations
Why can’t enum have a stored property? 


## UIColors 
> How to Apply Gradient to background view of iOS Swift App  
> [Gradient Color](https://stackoverflow.com/questions/24380535/how-to-apply-gradient-to-background-view-of-ios-swift-app)  


## UITextField Resources 
> Create space at the beginning of a UITextField  
> [Add padding to a UITextField ](https://stackoverflow.com/questions/25367502/create-space-at-the-beginning-of-a-uitextfield)  
>   
>   
``` swift
extension UITextField {
    func setLeftPaddingPoints(_ amount:CGFloat){
        let paddingView = UIView(frame: CGRect(x: 0, y: 0, width: amount, height: self.frame.size.height))
        self.leftView = paddingView
        self.leftViewMode = .always
    }
    func setRightPaddingPoints(_ amount:CGFloat) {
        let paddingView = UIView(frame: CGRect(x: 0, y: 0, width: amount, height: self.frame.size.height))
        self.rightView = paddingView
        self.rightViewMode = .always
    }
}
```

### UITabBarController 
> Tab bar Controller Image Size Issue   
> [Tab Bar Controller Image Size ](https://stackoverflow.com/questions/45189546/swift-3-tab-bar-controller-image-size-issue)  


