<h1 id="u-s-department-of-labor-top-hat-plan-data">U.S. Department of Labor Top Hat Plan data</h1>

<p>What this repository contains:</p> 
<ol>
  <li>Top Hat Data, obtained via FOIA request from the U.S. Department of Labor</li>
  <li>That data, supplemented with links to additional sources of employer information (specifically, Paycheck Protection Program data and WARN alerts)</li>
</ol>

<p>As mentioned, the centerpiece data in this repository comes from the U.S. Department of Labor. A <a rel="noreferrer noopener" href="https://www.askebsa.dol.gov/tophatplansearch" data-type="URL" data-id="https://www.askebsa.dol.gov/tophatplansearch" target="_blank">limited-feature search portal</a> is available on DOL's website (as of 12/4/2021) to download "top hat statement" pdf files. However, this portal lacks key contextual information (<a href="https://www.askebsa.dol.gov/efile/Home/tophat" target="_blank" rel="noreferrer noopener">input via form</a>). Thankfully, that additional contextual information is available in a dataset format.</p>

<p class="has-medium-font-size"><strong>What are Top Hat Plans?</strong></p>

<p>Top hat plans are "unfunded, nonqualified deferred compensation plans covering a 'select group of management or highly compensated employees.'" </p>

<p>"Top hat pension plans are a type of nonqualified deferred compensation (NQDC) arrangement. Employers maintain NQDC plans for a number of reasons, including recruiting employees, incentivizing employees to remain employed for a specified period (sometimes referred to as a 'golden handcuffs' arrangement), and supplementing retirement benefits provided under tax-qualified retirement plans."</p>

<p class="has-medium-font-size"><strong>Okay... How Does  "Deferred Compensation Plan" become "Qualified?" And What's a "Nonqualified" Deferred Compensation Plan?</strong></p>

<p>A "qualified" deferred compensation plan is a pension plan governed under the Employee Retirement Income Security Act (ERISA). Contributions made to a "qualified" deferred compensation plan are put into a trust that is separate from an employer's operations. Traditional 401(k)s or 403(b)s are types of "qualified" deferred compensation plans. </p>

<p>A "nonqualified" deferred compensation plan works differently. Compensation contributed to these plans is considered part of an employer's assets, and can be used by that employer for business reasons. Furthermore, if an employer goes bankrupt, the target-employee of this "nonqualified" deferred compensation plan is considered an unsecured creditor. And as described above, "nonqualified" deferred compensation plans are designed to incentivize employee longevity. In practice, this means if an employee fails to satisfy the terms of a deferred-compensation contractual arrangement, the employer does not owe this employee compensation. </p>

<p class="has-medium-font-size"><strong>I Still Don't Get It</strong></p>

<p>As an example, consider President Brown at State University. Let's say President Brown's employment contract establishes in 2015 a "nonqualified" deferred compensation plan for her. And State University is contractually obligated to annually credit $100,000 this "nonqualified" deferred compensation plan on July 1st of each of the following years: 2016, 2017, 2018, 2019, and 2020 — as long as President Brown is still employed at State University.</p>

<p>President Brown's deferred-compensation arrangement also sets the plan's vesting date as July 1, 2020, but again only if President Brown is still an employee of State University. No retiring early. No leaving for a cooler job somewhere else. President Brown has to still be with State University on July 1, 2020. 

<p>When 7/1/2020 arrives, if President Brown is still an employee of State University, State University will owe President Brown at least $500,000 that State University has been contractually crediting towards that "nonqualified" deferred compensation plan since 2016. This compensation is likely in addition to the base compensation she traditionally is paid every year, along with any performance-based bonuses, allowances, or other perks. 

<p>But if President Brown seperates from State University any time before 7/1/2020, State University no longer needs to credit money towards that "nonqualified" deferred compensation plan. Nor does it need to anticipate owing President Brown any taxable compensation in 2020.</p>

<p class="has-medium-font-size"><strong>Okay... What Makes a Nonqualified Deferred Compensation Plan "Unfunded" Instead of "Funded?"</strong></p>

<p>The "unfunded" or "funded" status of a plan indicates how it's future payments will financed.</p>

<p>When a deferred compensatioin plan is "funded," an employer is actively and systemically setting aside cash in advance to cover the employer's obligations as defined by the deferred-compensation contractual arrangement.</p>

<p>When a deferred compensation plan is "unfunded," the payments made by virtue of the plan are originating from the current income generated by the employer. No money is being set aside in advance.</p> 

<p class="has-medium-font-size"><strong>What Else Should I Know About This Data?</strong></p>

<p>Only non-government entities are required to submit "top hat statements" to DOL. That means publicly traded companies, privately held companies, and private, non-profit companies (hereafter referred to as "private companies).</p>

<p>To avoid all the regulation and scrutiny that comes with ERISA, these private companies must submit a "top hat statement" to DOL within 120 days of the top hat plan's establishment date. In practice, this "statement" takes the form of:</p>

• the name and address of the employer;
• the employer identification number (EIN);
• a declaration that the employer maintains plan(s) primarily for the purpose of providing
deferred compensation for a select group of management or highly compensated
employees; and
• a statement of the number of such plans and the number of employees in each plan.

<p><i>Reporting note: When The Chronicle interviewed the represenatives of university-employers that established tophat plans for their presidents, these representatives sought to create a distinction between a tophat plan's purported "establishment date" and the period in which the same tophat plan had been conceived as a result of contract negotiations with a president. All represenatives claimed the "establishment" of a plan had been a mere formality, and that pre-pandemic contract extensions or negotiations were a more accurate point of comparison for The Chronicle to use in any of its reporting.</i></p>

<p class="has-medium-font-size"><strong>You Better Download The Actual Top Hat Statements</strong></p>

For whatever reason, the top hat dataset obtained from DOL fails to include all of the contextual information present in electroinically submitted top hat statements. For instance, consider this row from the dataset, which concerns a filing from Assumption University, dated 9/9/2020: 

Filing Date: 9/9/2020
Filing Type: Tophat
Filing Method: Electronic
Sponsor EIN: 42105776
Filing Name: Assumption University
Plan Name or Paper Filing Notes: Assumption University 457(f) Deferred Compensation Plan
Employer Name: Assumption University
Employer Address 1: 500 Salisbury Street
Employer Address 2
Employer City: Worcester
Employer State: MA
Employer Zip Code: 01609
Participants: 1
No. of Plans in Filing: 1
No. of Filings: 1

But when you download the actual statement pdf file from DOL's portal, we learn some additional information about this plan. There's the name of the plan adminstrator, their contact information, and this ...

"The Plan is effective as of July 1, 2020 and was adopted on September 8, 2020. The Plan has one participant (Francesco C. Cesareo, Ph.D.)."

Francesco C. Cesareo is the president of Assumption University. Obviously, that is some very important information for my reporting that I wouldn't have known about had I not downloaded the actual statement. 

<p class="has-medium-font-size"><strong>What's This Stuff About PPP Loans and WARN Alerts</strong></p>

Congizent of the value information contained in this dataset, I took the time to query (by keyword) two additional sources of information before I published it here on Github. I added links to:
1. Hits I got using ProPublica's searchable database of Small Business Administration PPP loans
2. Hits I got searching through 2020-2021 WARN alerts published by 40+ states

<p class="has-medium-font-size"><strong>I Can't Stress This Enough</strong></p>

Conduct your own due dillegence when it comes to these PPP and WARN alerts supplements! Why? 

A: My searches were cursory

A: My appetite for entertaining false positives was greater than I'd stomach otherwise, given that I didn't intend to write about these particular datapoints or PUBLISH-PUBLISH this dataset. 

A: I didn't care to learn about the technical nuances of each state's WARN-alert systems. So I can't tell you why some states record even minor layoff events, while others barely track any.

A: Because of the time, learning curve, and grunt work involved, I didn't integrate additional datapoints into this file, like data about federal Covid-relief to specific industries. Think airlines, colleges, or hospitals. I also couldn't conceptualize an effective and comprehensive strategy for identifying other pandemic-era workplace events. All I could come up with was "do a billion Google searches with different keywords AND 'company name.' Never see family or friends again." So, yeah, I passed on that. 

A: I did integrate PPP loan "keyword" matches into this dataset. You SHOULD NOT consider that integration a blanket endorsement FROM ME to UNCRITICALLY CITE the existence of Covid-relief information within any final editorial product you generate. We had a vigorous debate at The Chronicle about what it meant for a college or university to seek out and/or accept federal relief during this pandemic. You should undertake a similar debate within yourself and/or your own newsroom if you are considering using PPP data, WARN alert data, or other supplementary data when reporting on these plans — even if you ultimately arrive at a different decision than The Chronicle did. Ultimately, the references to PPP data remain present in the file because it's possible additional reporting by and context from you may justify its reference in a final editorial product. 
