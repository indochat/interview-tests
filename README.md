# iOS Interview Test

## Overview
Create an iOS project from scratch.
Show a list of the cat images from [CATAAS](https://cataas.com/#/).
When clicking a cat image, display the cat **tags** (get from API) on the detail screen.

## Requirement
- Use Swift 4.0 or above.
- Fetch the data from the REST API provided by [CATAAS](https://cataas.com/#/)
- Parse the network response and present the information to the user using [Codable](https://developer.apple.com/documentation/swift/codable).
- Show cats images in your UITableViewCell/UICollectionViewCell.
- Show the cat's full information in the detail page when clicking a cat image
- You can use any 3rd party libraries you wish (Alamofire, kingfisher, SwiftEntryKit, etc) but be prepared to justify why you did so. Feel free to use package managers like [CocoaPods] (https://cocoapods.org/) to handle them.


## Extra points
- Implement pagination in UITableView/UICollectionView and get at most 20 cat data per REST API request.
- Support offline mode.
- Unit Test or UI Test.

## Image Url
- format: https://cataas.com/cat/[cat_id]
- example: https://cataas.com/cat/595f280a557291a9750ebf58 \
![https://cataas.com/cat/595f280a557291a9750ebf58](https://cataas.com/cat/595f280a557291a9750ebf58)

## Sample screenshot
![Screen Shot 2021-04-20 at 14 38 42](https://user-images.githubusercontent.com/197605/115351425-d1d7d680-a1e8-11eb-9a05-433979a3cc84.png)
![Screen Shot 2021-04-20 at 14 46 06](https://user-images.githubusercontent.com/197605/115351467-dbf9d500-a1e8-11eb-8567-0755b1d58e14.png)
