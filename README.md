# iOS Interview Test

## Overview
Create an iOS project from scratch.
Show a list of the cat images from [CATAAS](https://cataas.com/#/).
When clicking a cat image, display the cat **tags** (get from API) on the screen.

## Requirement
- Use Swift 4.0 or above.
- Fetch the data from the REST API provided by [CATAAS](https://cataas.com/#/)
- Parse the network response and present the information to the user using [Codable](https://developer.apple.com/documentation/swift/codable).
- Show cats images in your UITableViewCell/UICollectionViewCell.
- Toast the cat's tags on the screen when clicking a cat image
- It should compile and run.
- You can use any 3rd party libraries you wish (Alamofire, kingfisher, SwiftEntryKit, etc) but be prepared to justify why you did so. Feel free to use package managers to handle them.


## Extra points
- Implement pagination in UITableView/UICollectionView and get at most 20 cat data per REST API request.
- Support offline mode.
- Write your XCTestCase.

## Image Url
- format: https://cataas.com/cat/[cat_id]
- example: https://cataas.com/cat/595f280a557291a9750ebf58 \
![https://cataas.com/cat/595f280a557291a9750ebf58](https://cataas.com/cat/595f280a557291a9750ebf58)

## Sample screenshot
![](https://github.com/indochat/interview-tests/blob/android/sample.jpg)
