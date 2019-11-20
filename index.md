---
layout: blocks
title: Multiple Chronic Conditions Tool
date: 2017-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2019/07/29/LOGO-TEMP.png"
  navigation:
  - link: ''
    link_text: ''
  cta:
    url: https://github.com/usnish/MCC_cluster_tool
    button_text: Download
- template: hero-banner-w-image
  block: hero-2
  headline: Multiple Chronic Conditions Tool<br><strong>for population health analytics</strong>
  content: The MCC Tool is a library of python tools designed to help health system
    administrators, population health strategists, and health services researchers
    explore patterns of co-morbidity and cost among patients with multiple chronic
    conditions.
  cta:
    enabled: true
    url: https://github.com/usnish/MCC_cluster_tool
    button_text: 'See on GitHub '
  image:
    image: "/uploads/2019/09/25/home-2.png"
    alt_text: Product Shot
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>About </strong>the MCC Tool"
  content: '<strong>Multiple Chronic Conditions<br></strong>Rates of multimorbidity
    are rising globally. Overall, 42% of adults have multiple chronic conditions (MCC);
    that number rises to over 80% of those over 65 years of age. In the United States,
    patients with multiple chronic conditions account for an estimated 70% of all
    healthcare spending. Health systems have responded to this increasing burden by
    implementing financial and clinical innovations to improve quality and keep costs
    under control.Gaps in what is known about the global MCC burden persist. For example,
    much of what is studied focuses on older adults, while there has been less research
    on younger adults and those who live in low- and middle-income countries. In addition,
    while there is some evidence regarding the most common clusters of chronic conditions
    in a given area, less is known about the myriad ways multimorbidity can occur
    in a patient or group of patients.<br><br><strong>The MCC Tool<span style="text-decoration:
    underline;"><br></span></strong>A standard methodology to evaluate the prevalence
    and associated costs of patients with multiple chronic conditions could be beneficial
    to health systems, researchers, and governments as they implement new care models
    and financial incentives to achieve quality and cost goals. We designed a tool
    to help determine which segments of a given population have specific multiple
    chronic conditions. The main purpose is to provide health systems analysts with
    a simple descriptive method that can be applied to any population for whom medical
    claims data are available. Importantly, this tool allows the exploration of multimorbidity
    without any assumptions (i.e. that may come from more complex statistical or machine
    learning techniques) or demographic limitations.<br><br>In addition, it can help
    sort health systems data by prevalence and attributed spending of multiple chronic
    conditions. The key functionality of this tool lies in defining, navigating, and
    sorting <strong>‘segments’ </strong>within a population. Here we define ‘Segments’
    as a group of patients defined by 1 or 2 chronic conditions, an age group, and
    legal sex (‘M’ or ‘F’, as represented in insurance claims data). These fields
    are commonly found in existing insurance claim data sets.'
  media:
    image: "/uploads/2019/08/05/questions-1.png"
    alt_text: FAQ
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: <strong>Requirements<span class="light"> </span></strong><span class="light">for
    the tool</span>
  content: '<strong>This package is built to run on Python 3.6.7.</strong><br><br>The
    requirements to use this tool are:<br><br>A health insurance claims data set (or
    equivalent healthcare dataset -- whether from an Electronic Health Record or epidemiologic
    survey) made with the International Classification of Diseases version 9 (ICD-9)
    with at least the following variables, aggregated by member-year:<br><br>Age<br>Gender<br>Location<br>Chronic
    condition codes<br>Total cost of care<br>Python language software package is built
    to run on Python 3.6.7.<br><br>These additional libraries (for more information,
    see requirements.txt):<br><br><strong>seaborn==0.9.0<br>matplotlib==3.0.2<br>pandas==0.23.4<br>scipy==1.1.0<br>numpy==1.15.4<br><br></strong>You
    can download the package at its GitHub here: <a href="https://github.com/usnish/MCC_cluster_tool"
    title="https://github.com/usnish/MCC_cluster_tool"><span style="text-decoration:
    underline;">https://github.com/usnish/MCC_cluster_tool</span></a><br><br><br>'
  media:
    image: "/uploads/2019/08/05/resources.png"
    alt_text: uBuild Blocks Mock-Up
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Getting<strong> Started</strong>
  content: If you have git you can<br><br><strong>$ git clone </strong><a href="https://github.com/usnish/MCC_cluster_tool.git"
    title="https://github.com/usnish/MCC_cluster_tool.git"><strong>https://github.com/usnish/MCC_cluster_tool.git</strong></a>
  media:
    image: "/uploads/2019/08/05/packet.png"
    alt_text: ''
- template: hero-banner-w-image
  block: hero-2
  image:
    image: "/uploads/2019/08/05/showcase.png"
    alt_text: ''
  headline: EXAMPLES <strong>SHOWCASE</strong>
  content: Coming soon
  background_image: "/uploads/2019/08/05/bg-2.png"
  cta:
    enabled: false
    url: ''
    button_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: License
  content: 'This code is available for free use under the terms of the <a href="https://www.gnu.org/licenses/lgpl-3.0.en.html"><span
    style="text-decoration: underline;">GNU LGPLv3.</span></a>Per Github: Permissions
    of this copyleft license are conditioned on making available complete source code
    of licensed works and modifications under the same license or the GNU GPLv3. Copyright
    and license notices must be preserved. Contributors provide an express grant of
    patent rights. However, a larger work using the licensed work through interfaces
    provided by the licensed work may be distributed under different terms and without
    source code for the larger work.<br><br>Read the full text of the MCCTool license
    <a href="https://github.com/usnish/MCC_cluster_tool/blob/master/LICENSE"><span
    style="text-decoration: underline;">here</span></a>.<br><br><strong>References:<br></strong>Majumdar
    UB, Hunt C, Doupe P, et al.<em> </em>Multiple chronic conditions at a major urban
    health system: a retrospective cross-sectional analysis of frequencies, costs
    and comorbidity patterns. <em>BMJ Open </em>2019;9:e029340. doi: 10.1136/bmjopen-2019-029340<br><br>Hajat
    C, Kishore SP. The case for a global focus on multiple chronic conditions. <em>BMJ
    Global Health </em>2018;<strong>3:</strong>e000874.<br><br>The Academy of Medical
    Sciences. (2018). <em>Multimorbidity: a priority for global health research. </em>Retrieved
    from <a href="https://acmedsci.ac.uk/file-download/82222577" title="https://acmedsci.ac.uk/file-download/82222577">https://acmedsci.ac.uk/file-download/82222577</a>)'
  media:
    image: "/uploads/2019/08/05/copyleft.png"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>FAQ</strong>"
  content: '<strong>How do I generate chronic disease categories for this tool?<br></strong>We
    have built this tool to be readily compatible with the ICD-9 diagnosis code: chronic
    disease category mapping available from the <a href="https://www.hcup-us.ahrq.gov/toolssoftware/chronic/chronic.jsp"><span
    style="text-decoration: underline;">Healthcare Cost and Utilization Project</span></a>.
    What does this mean? If you have data that attributes an <a href="https://www.cdc.gov/nchs/icd/icd9cm.htm"
    title="">ICD-9 diagnosis code</a> to patients, you can group similar diagnoses
    together into a broader chronic disease category. For example, diagnosis code
    250.52 (“Diabetes with ophthalmic manifestations, type II or unspecified type,
    uncontrolled”) and 250.00 (“Diabetes mellitus without mention of complication,
    type II or unspecified type, not stated as uncontrolled”) would be grouped together
    into the chronic disease category ‘Type II Diabetes Mellitus’.<br><br><strong>What
    format does my healthcare data need to be in? <br></strong>In order to utilize
    this tool, you need to aggregate claims data by member-year. This means that each
    row in your data should represent a single member in a single year of utilization.
    If you are working with a different type of healthcare data (from an Electronic
    Health Record system, or an epidemiologic survey), you would want each row of
    your data to represent a unique individual in a given year. The below table gives
    a simplistic overview of what this could look like:<br><br>TABLE HERE<br><br><strong>How
    should I go about generating segments?<br></strong>Utilize SampleSegmentation.ipynb
    with your existing data to generate a sample set of segments and visualizations.
    Leave an issue on the github page or contact <strong>usnishm@gmail.com</strong>
    if you have any additional questions.<br><br><strong>What should I do if I have
    problems?<br></strong>If you are having problems or have found a bug in the code,
    please raise an issue on the Github page here: <a href="https://github.com/usnish/MCC_cluster_tool/issues"
    title="https://github.com/usnish/MCC_cluster_tool/issues"><span style="text-decoration:
    underline;">https://github.com/usnish/MCC_cluster_tool/issues</span></a>'
  media:
    image: "/uploads/2019/08/05/troubleshooting-1.png"
    alt_text: ''
- template: 4-column-footer
  block: footer-2
  col_2: '<strong><img src="/uploads/2019/09/25/AIGH-logo.png"><br><br>Arnhold Institute
    for Global Health</strong><br>Tel: 212-824-7950<br>arnholdInstitute@mssm.edu<br><br>1216
    Fifth Avenue <br>Fifth Floor, Room 556 <br>New York, NY 10029'
  col_3: ''
  image: "/uploads/2019/08/05/copyleft-1.png"
  col_4: Supported by<br><br><img src="/uploads/2019/08/05/teva-1.png">

---
foo bar