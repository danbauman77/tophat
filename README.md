<h1>U.S. Department of Labor Top Hat Plan data</h1>

<p>What this repository contains:</p> 
<ol>
  <li>Top Hat Plan data, obtained via FOIA request to the U.S. Department of Labor</li>
  <li>That data, supplemented with links to additional sources of employer information (specifically, Paycheck Protection Program and WARN alert data points)</li>
</ol>

<p>As mentioned, the centerpiece data in this repository comes from the U.S. Department of Labor. A <a rel="noreferrer noopener" href="https://www.askebsa.dol.gov/tophatplansearch" data-type="URL" data-id="https://www.askebsa.dol.gov/tophatplansearch" target="_blank">limited-feature search portal</a> is available on DOL's website (as of 12/4/2021) to download "top hat statement" pdf files. However, this portal lacks key contextual information (<a href="https://www.askebsa.dol.gov/efile/Home/tophat" target="_blank" rel="noreferrer noopener">input via web form by employers</a>). Thankfully, that additional contextual information is available in a dataset format.</p>

<p><h2><strong>What are Top Hat Plans?</strong></h2></p>

<p>Top hat plans are "unfunded, nonqualified deferred compensation plans covering a 'select group of management or highly compensated employees.'"<sup>1</sup> </p>

<p>"Top hat pension plans are a type of nonqualified deferred compensation (NQDC) arrangement. Employers maintain NQDC plans for a number of reasons, including recruiting employees, incentivizing employees to remain employed for a specified period (sometimes referred to as a 'golden handcuffs' arrangement), and supplementing retirement benefits provided under tax-qualified retirement plans."<sup>2</sup></p>

<p><h2><strong>Okay... What Is The Difference Between a "Qualified" Deferred Compensation Plan and a "Nonqualified" Plan?</strong></h2></p>

<p>A "qualified" deferred compensation plan is a pension plan governed under the Employee Retirement Income Security Act (ERISA).<sup>3</sup> Contributions made to a "qualified" deferred compensation plan are put into a trust that is separate from an employer's operations.<sup>4</sup> Traditional 401(k)s or 403(b)s are types of "qualified" deferred compensation plans.<sup>4</sup></p>

<p>A "nonqualified" deferred compensation plan works differently. Compensation contributed to these plans is considered part of an employer's assets, and can be used by that employer for business reasons.<sup>5</sup> Furthermore, if an employer goes bankrupt, the target-employee of this "nonqualified" deferred compensation plan is considered an unsecured creditor.<sup>6</sup>  And as described above, "nonqualified" deferred compensation plans are designed to incentivize employee longevity. In practice, this means if an employee fails to satisfy the terms of a deferred-compensation contractual arrangement, the employer does not owe compensation to that employee. </p>

<p><h2><strong>I Still Don't Get It</strong></h2></p>

<p>As an example, consider President Sarah Brown at Hoover University. Let's say President Brown's employment contract results in the establishment, in 2020, of a "nonqualified" deferred compensation plan for her. And Hoover University is contractually obligated to annually credit $100,000 into this "nonqualified" deferred compensation plan. Specifically, that creditting will occur on July 1st of each of the following years: 2021, 2022, 2023, 2024, and 2025 — as long as Brown is still employed at Hoover U.</p>

<p>President Brown's deferred-compensation arrangement also sets the plan's vesting date as July 1, 2025 — but again only if Brown is still an employee of Hoover University on that date. No retiring early. No leaving for a cooler job somewhere else. To be owed the money that will be credited towards her deferred compensation plan, Brown must still be an employee of Hoover U. on July 1, 2025. 

<p>When 7/1/2025 arrives, if Brown is still an employee of Hoover U., HU will owe Brown at least $500,000 — compensation that Hoover University has been contractually crediting towards Brown's "nonqualified" deferred compensation plan since 2021. This compensation is likely in addition to the base compensation that Brown is traditionally paid every year, alongside any performance-based bonuses, allowances, or other perks. 

<p>But if Brown seperates from Hoover U. any time before 7/1/2025, HU no longer needs to credit money towards Brown's "nonqualified" deferred compensation plan. Nor does Hoover U. need to anticipate owing Brown any taxable compensation in 2025.</p>

<p><h2><strong>Okay... What Makes a Nonqualified Deferred Compensation Plan "Unfunded" Instead of "Funded?"</strong></h2></p>

<p>The "unfunded" or "funded" nature of a plan indicates how its future payments will financed.</p>

<p>When a deferred compensatioin plan is "funded," an employer is actively and systemically setting aside cash in advance to cover the employer's obligations as defined by the deferred-compensation contractual arrangement.<sup>7</sup></p>

<p>When a deferred compensation plan is "unfunded," the payments made by virtue of the plan are originating from the current income generated by the employer. No money is being set aside in advance.<sup>7</sup></p> 

<p><h2><strong>What Else Should I Know About This Data?</strong></h2></p>

<p>Only non-government entities are required to submit "top hat statements" to DOL. That includes publicly traded companies, privately held companies, and private, non-profit companies (hereafter all referred to collectively as "private companies").</p>

<p>To avoid all the regulation and scrutiny that comes with ERISA, these private companies must submit a "top hat statement" to DOL within 120 days of the top hat plan's establishment date. In practice, this "statement" takes the form<sup>1</sup> of:</p>

<ul>
  <li>the name and address of the employer;</li>
  <li>the employer identification number (EIN);</li>
  <li>a declaration that the employer maintains plan(s) primarily for the purpose of providing
  deferred compensation for a select group of management or highly compensated
  employees; and</li>
  <li>a statement of the number of such plans and the number of employees in each plan.</li>
</ul>

<p>Reporting note: <i>When The Chronicle interviewed the represenatives of university-employers that established tophat plans for their presidents, these representatives sought to create a distinction between a tophat plan's purported "establishment date" and the time period during which the same tophat plan was conceived of — usually as a result of contract negotiations between a university's governing board and its president. All represenatives claimed the "establishment" of a plan had been a mere formality, and that pre-pandemic contract extensions or negotiations were a more accurate point of comparison for The Chronicle to use in any of its reporting.</i></p>

<p><h2><strong>You Better Download The Actual Top Hat Statements</strong></h2></p>

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
