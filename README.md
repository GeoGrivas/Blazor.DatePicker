# Blazor.DatePicker

A simple Blazor Date/Range picker written 100% in C#. 

You can check it out here https://blazor.adventurouscoding.com

Parameters 
<ul>
<li>SingleDate(bool): Single Date mode</li>
<li>InlineMode(bool) : Inline display (otherwise it will pop on click)</li>
<li>Culture(CultureInfo) : Multi cultural(not RTL though)</li>
<li>MinDays/MaxDays(int) : Min/Max days that can be picked</li>
<li>NumberOfMonthsToDisplay(int) : Number of months to display</li>
<li>DateFormat(string) : Date display format</li>
<li>Placeholder(string) : input placeholder</li>
<li>MinimumDate/MaximumDate(DateTime?) : Min/Max available date</li>
<li>InitialMonth/InitialYear(int) : Starting month/year</li>
<li>BlockedDates(List<DateTime>) : Blocked dates</li>
<li>OnDateSelected(EventCallback<string>) : Returns picked date or date range when successfully selected</li>
</ul>
