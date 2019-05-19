# ProfileActions
Sample Application to display the profile activities of abp weddings user.


Requirements:

Please create a project as per the following.
1) Two dropdowns at the top:
a) Year - 2017, 2018, 2019 (Latest year ‘2019’ should be selected
by default)
b) Month - January, February, March, April, May, June, July,
August, September, October, November, December. (Latest
month ‘April’ should be selected by default)
2) A List that populates the data in DESC order based on date (April 24,
2019 , April 23, 2019, April 20, 2019 …)
3) Each row in the List, should reflect the following:
- Icon (You can place any icon)
- Type of activity (Profile View, Not my Type etc.)
- Activity description
- Time of activity.
URL: Parse the json from the following url
URL format:
https://sof.abpweddings.com/mats/activity/read/2180746/<year>/<mo
nth>/0.json
Example:
March 2019:
https://sof.abpweddings.com/mats/activity/read/2180746/2019/3/0.jso
n
April 2019:
https://sof.abpweddings.com/mats/activity/read/2180746/2019/4/0.jso
n
On selecting Year and Month from the Dropdown, it’ll fetch and
populate the data in the RecyclerView.
