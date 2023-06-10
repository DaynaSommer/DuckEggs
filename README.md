# DuckEggs

A computer program is required to assess the weekly production of duck eggs.

The program must initially accept the date and the current price for which three sizes of eggs (medium, large, and jumbo) will be sold. These prices may change, so the program must be able to accommodate these changes.

Following that, data from collections made that week will be entered. These will consist of the number and size of eggs obtained at each collection. The size of those eggs will be indicated by the code letter M, L, or J. The number of collections for a given duck will vary each week, so a flag of 99 in the number of eggs field will indicate completion of data for that duck. Similarly, the duck population will vary from report to report so a flag value of DONE will be used to indicate all ducks have been entered. All inputs will come from the keyboard.

The program must output a report to the screen. For each collection, the report must display the number and size of eggs obtained as well as the value of that collection. This value is calculated as the product of the number of eggs and the price for that specific sized egg.

For each duck, the report must display the total number eggs produced by that duck, as well as the dollar value of that production.

Finally, a summary must display to the screen, the date of the report, the average numbers of eggs produced (calculated as total number of eggs divided by total number of ducks), the code number of the duck that produced the largest number of eggs for this period and how may eggs that corresponded to, and also the code number of the duck whose dollar production was the lowest, as well as what that dollar figure was. In the event of multiple instances of both these extreme, only the first instance is to be reported.
