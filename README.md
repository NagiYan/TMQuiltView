# TMQuiltView
 Interface similar to the UITableView with UI similar to Pintrest. 
 from Homepage: https://github.com/1000Memories/TMQuiltView  ， 
 
 	2015.12.31
	1 improved UI performance
	2 added headerView
	3 cache height

    UIView* header = [UIView new];
    [header setFrame:CGRectMake(0, 0, GScreenWidth, 300)];
    [header setBackgroundColor:FlatMint];
    [_tableView setHeaderView:header];
