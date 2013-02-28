MABadgeView
===========

Self-contained custom UIView for badge indicators (similar to UITabBarItem). Fork of NIBadgeView from nimbus, with no external depenencies.

Usage:
------

    NIBadgeView* badgeView = [[NIBadgeView alloc] initWithFrame:CGRectZero];
    badgeView.text = @"7";
    badgeView.backgroundColor = [UIColor clearColor];
    [badgeView sizeToFit];
    [self.view addSubview:badgeView];
