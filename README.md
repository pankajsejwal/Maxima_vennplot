Maxima_vennplot
===============

Plotting venn diagram for logical relations on Maxima.
Usage:
vennplot(number-of-sets,logical_relation,[list of logical atoms])
example,
        vennplot2(1,not(a),[a]);
        vennplot(2,a and  not(b) ,[a,b]);
        vennplot2(3,a and b or (c) or d,[a,b,c]);

