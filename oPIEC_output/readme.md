## oPIEC output

A separate output file is created for each input dataset and target complex event. The name of each file is "${InputName}\_${FluentName}\_${FluentValue}.result". For example, "caviar_test_meeting_true.result" contains the maximal intervals during which "meeting" occurs in the test case of the provided caviar example. The format of every line of the file is "${FluentName}\_${Arg1}\_${Arg2}\_...\_${ArgN} : [(${Interval1},${Interval2},...,${IntervalM})]". Every interval is right-open and represented as a tuple: (${start}, ${end}}). 