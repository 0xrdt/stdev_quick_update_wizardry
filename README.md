# stdev_quick_update_wizardry
O(n) exact algorithm to calculate the new stdev of an set of points after the insertion of a new value given the number of points, old stdev and old mean. The idea to make this algorithm came from the Messari Subgraphs Discord
> The key insight for this method is that new_std*(new_len-1)-old_std*(old_len-1)=(new_val-new_mean)(new_val-old_mean)
