---
layout: default
---

<style>
#toc_container {
    background: none repeat scroll 0 0;
    display: table;
    font-size: 95%;
    margin-bottom: 1em;
    width: auto;
}
#toc_container li, #toc_container ul, #toc_container ul li{
    list-style: outside none none !important;
}

/* Floating button by JakeFromSF at https://stackoverflow.com/questions/32102747/how-to-make-a-back-to-top-button-using-css-and-html-only */
/*Floating Back-To-Top Button*/
#myBtn {
  position: fixed;
  bottom: 10px;
  float: right;
  right: 18.5%;
  left: 77.25%;
  max-width: 30px;
  width: 100%;
  font-size: 12px;
  border-color: rgba(85, 85, 85, 0.2);
  background-color: rgb(100,100,100);
  padding: .5px;
  border-radius: 4px;
}
/*On Hover Color Change*/
#myBtn:hover {
  background-color: #7dbbf1;
}

</style>

<button id="myBtn"><a href="#top" style="color: white">Top</a></button>

# Frequently Asked Questions

<div id="toc_container">
<ul class="toc_list">
  <li><a href="#FinTech">FinTech</a>
  <ul>
    <li><a href="#What_is_FinTech">What is FinTech?</a></li>
    <li><a href="#What_is_PayTech">What is PayTech?</a></li>
    <li><a href="#What_is_CreditTech">What is CreditTech?</a></li>
  </ul>
  </li>
  <li><a href="#DataScience">Data Science</a>
  <ul>
    <li><a href="#What_is_NLP">What is Natural Language Processing?</a></li>
    <li><a href="#What_is_ML">What is Machine Learning?</a></li>
    <li><a href="#What_is_SNA">What is Social Network Analysis?</a></li>
  </ul>
  </li>
</ul>
</div>

<h2 id="FinTech">FinTech</h2>

<h4 id="What_is_FinTech">What is <em>FinTech</em>?</h4>

FinTech is the implementation of new technology with the intent to improve the efficiency or performance of financial products or services.  The adaptation of technological innovation to financial problems includes, but is not limited to, payment systems, credit analysis, investment management, and blockchain ledgers.

<h4 id="What_is_PayTech">What is <em>PayTech</em>?</h4>

PayTech seeks to improve efficiencies in transactions.  In some instances, this consists of providing a more user-friendly front-end to an existing infrastructure.  In other cases, a new payment infrastructure is created that offers decreased transaction costs.

<h4 id="What_is_CreditTech">What is <em>CreditTech</em>?</h4>

"Credit is the ability to borrow money or access goods or services with the understanding that you'll pay later" [(Experian)](https://www.experian.com/blogs/ask-experian/credit-education/faqs/what-is-credit/).  CreditTech utilizes technological advancements in data acquisition (e.g. "big data") to supplement a consumer's existing credit score with additional information.  Additionally, CreditTech employs technology to assess the creditworthiness of consumers who do not have a credit score.  This latter innovation is important -- 22% of adults in the United States do not have a FICO credit score [(fool.com)](https://www.fool.com/the-ascent/credit-cards/articles/22-of-americans-dont-have-a-credit-score-heres-why/).

<h2 id="DataScience">Data Science</h2>

Data science combines statistics and data to solve problems.  The explosion of data science in the 21st century is attributable to two factors.  First, computer processing power advanced exponentially; computers are now capable of handling incredibly complex and computationally demanding tasks.  This made more sophisticated statistical techniques more feasible to implement.  Second, advancements in our ability to generate, collect, and store information about our world created a wealth of data.  This data, when correctly fed to statistical routines, can reveal new insights.  Data science capitalizes on these insights.

<h4 id="What_is_NLP">What is <em>Natural Language Processing</em>?</h4>

"Natural language processing (NLP) is a branch of artificial intelligence that helps computers understand, interpret and manipulate human language" [(SAS)](https://www.sas.com/en_us/insights/analytics/what-is-natural-language-processing-nlp.html).

Consider the disclosure of risk factors in a firm's annual report.  Finance is about the study of risk and return, after all!  In 2019, a total of 52 *million* words were used by companies in their risk disclosure.  To read over all of these disclosures within the span of one year, a human would need to read the equivalent of all seven Harry Potter books *each and every week*.  A computer, in contrast, can read an analyze the totality of these disclosures in a matter of minutes!   Exctracting information from these disclosures is thus best left to the machines.  But how can a computer learn to read these disclosures?  How can a computer recognize whether a particular company in a given year is disclosing an exposure to cybersecurity risk?  How can a computer determine whether a company's risk disclosure this year is any different from the disclosure that it submitted last year?  NLP techniques provide solutions to these questions.  FI.lab researchers have applied NLP to study management personality and its effect on the valuation of firm resources and to investigate the risk disclosure practices of public firms.

<h4 id="What_is_ML">What is <em>Machine Learning</em>?</h4>

"Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it to learn for themselves" [(expert.ai)](https://www.expert.ai/blog/machine-learning-definition/).  Examples of machine learning in finance are described in a blog post at [Algorithm-X Lab](https://algorithmxlab.com/blog/applications-machine-learning-finance/).  FI.lab researchers have applied Machine Learning methods for natural language understanding (NLU).  NLU is an sub-branch of NLP (discussed above) that teaches a computer to read language and interpret it as a human would.  For instance, consider the text:
> ALice Smith, CEO of XYZ Inc. remains hopeful.  When asked by analysts about expectations for the next fiscal year, she indicated that earnings growth would remain at recent levels.

A human can examine the pair of sentences and understand that the "she" in the latter sentence refers to "Alice" in sentence one.  With applications of machine learning, a computer is able to do the same!

<h4 id="What_is_SNA">What is <em>Social Network Analysis</em>?</h4>

"Social network analysis uses graph theory and network modeling techniques to investigate the dynamics of social networks, the formation, and evolution of communities, as well as information diffusion" [(Zhang et al. 2019)](https://www.sciencedirect.com/science/article/abs/pii/S0268401218310995).  FI.lab researchers have applied Social Network Analysis to study the incentives of directors to protect shareholder interests or to study the spread of risk perceptions across social groups.
