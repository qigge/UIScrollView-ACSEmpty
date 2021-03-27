# UIScrollView-ACSEmpty
UIScrollView  EmptyDataSet Placeholder View

Core code reference dzenbot/DZNEmptyDataSet.

When the data is empty, show the placeholder View you set.

If you don’t want to show the placeholder image before the network request comes back, please set the placeholder image after the network request is completed.


How to use

Import
#import "UIScrollView+ACSEmpty.h"


self.tableView.acs_emptyView = [UIView new];

or 

self.scrollview.acs_emptyView = [UIView new];

or

self.collectView.acs_emptyView = [UIView new];



