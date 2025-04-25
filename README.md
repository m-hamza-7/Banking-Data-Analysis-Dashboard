# Banking-Data-Analysis-Dashboard
Analyzed banking transaction data using Python (EDA), SQL (cleaning), and Power BI (dashboarding). Explored loan/deposit trends, customer demographics, and financial performance to optimize banking strategies.

## Project Objectives
  - Analyze loan and deposit distributions across customer segments.
  - Evaluate client demographics (gender, income, occupation) for targeted services.
  - Track yearly trends (2013–2021) in banking relationships.
  - Compare account types (checking, savings, business lending) for revenue insights.
  - Identify high-risk loan categories and deposit patterns.

## Key Metrics
<!-- Key Metrics Table -->
<table>
  <thead>
    <tr>
      <th><strong>Category</strong></th>
      <th><strong>Metric</strong></th>
      <th><strong>Value</strong></th>
    </tr>
  </thead>
  <tbody>
    <!-- Loans Section -->
    <tr>
      <td rowspan="3"><strong>Loans</strong></td>
      <td>Total Loan Amount</td>
      <td>4.38B</td>
    </tr>
    <tr>
      <td>Business Lending</td>
      <td>2.60B</td>
    </tr>
    <tr>
      <td>CC Balance</td>
      <td>9.53M</td>
    </tr>
    <!-- Deposits Section -->
    <tr>
      <td rowspan="3"><strong>Deposits</strong></td>
      <td>Total Deposit Amount</td>
      <td>3.77B</td>
    </tr>
    <tr>
      <td>Checking Accounts</td>
      <td>963.28M</td>
    </tr>
    <tr>
      <td>Savings Accounts</td>
      <td>698.73M</td>
    </tr>
    <!-- Clients Section -->
    <tr>
      <td rowspan="2"><strong>Clients</strong></td>
      <td>Total Clients</td>
      <td>3,000</td>
    </tr>
    <tr>
      <td>Gender Split (F/M)</td>
      <td>[Value]</td>
    </tr>
  </tbody>
</table>

## Visualizations

<ol>
  <li>
    <strong>Loan vs. Deposit Overview</strong>
    <ul>
      <li>Interactive tabs (<code>Loan Analysis</code>, <code>Deposit Analysis</code>) compare <strong>total loans </strong> and <strong>deposits</strong>.</li>
      <li><a href="https://github.com/m-hamza-7/Banking-Data-Analysis-Dashboard/blob/main/Home.png"><em>Image: Dashboard homepage with key metrics and toggle filters.</em></a></li>
    </ul>
  </li>
  <li>
    <strong>Customer Segmentation</strong>
    <ul>
      <li>Breakdown by <strong>gender</strong>, <strong>income band</strong> and <strong>occupation</strong>.</li>
      <li><a href="https://github.com/m-hamza-7/Banking-Data-Analysis-Dashboard/blob/main/Loan%20Analysis.png"><em>Image: "Bank Loan by Income Band" pie chart and occupation bar charts.</em></a></li>
    </ul>
  </li>
  <li>
    <strong>Trend Analysis (2013–2021)</strong>
    <ul>
      <li>Time-based filters show yearly trends in <strong>account growth</strong> (checking vs. savings) and <strong>business lending</strong>.</li>
      <li><a href="https://github.com/m-hamza-7/Banking-Data-Analysis-Dashboard/blob/main/Deposit%20Analysis.png"><em>Image: "Joining Year" filter with stacked column charts.</em></a></li>
    </ul>
  </li>
</ol>

<!-- Dashboard Insights Section -->
## Dashboard Insights

<ol>
  <li>
    <strong>Loan Analysis</strong>
    <ul>
      <li><strong>Income Band Impact</strong>:
        <ul>
          <li>Medium-income clients contributed <strong>53.12% (942.49M)</strong> of loans.</li>
          <li>High-income clients accounted for <strong>25.26% (446.19M)</strong>.</li>
        </ul>
      </li>
      <li><strong>Occupation Trends</strong>: Business lending dominated (<strong>2.60B</strong>).</li>
      <li><strong>Nationality/Risk</strong>: [Add specific insights from your data].</li>
    </ul>
  </li>
  <li>
    <strong>Deposit Analysis</strong>
    <ul>
      <li><strong>Income Band Distribution</strong>:
        <ul>
          <li>Medium-income clients held <strong>54.17% (1.00B)</strong> of deposits.</li>
          <li>Low-income clients contributed <strong>21.05% (0.62B)</strong>.</li>
        </ul>
      </li>
      <li><strong>Account Preferences</strong>: Checking accounts (<strong>963.28M</strong>) > Savings (<strong>698.73M</strong>).</li>
    </ul>
  </li>
  <li>
    <strong>Customer Segmentation</strong>
    <ul>
      <li><strong>Banking Relationships</strong>: Retail, Private Bank, Commercial.</li>
      <li><strong>Gender Split</strong>: Female vs. Male client ratios.</li>
      <li><strong>Yearly Trends</strong>: Growth from <strong>2013–2021</strong>.</li>
    </ul>
  </li>
</ol>
