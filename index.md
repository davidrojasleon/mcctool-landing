---
layout: blocks
title: Multiple Chronic Conditions Tool
date: 2017-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2019/07/29/LOGO-TEMP.png"
  navigation: []
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
  headline: <strong>Requirements<span class="light"> </span></strong><span class="light">for
    the tool</span>
  content: "<strong>This package is built to run on Python 3.6.7.</strong><br><br>This
    package is built to run on Python 3.6.7. You will need the following additional
    libraries (see  <strong>requirements.txt</strong> ):<br><br><strong>seaborn==0.9.0<br>matplotlib==3.0.2<br>pandas==0.23.4<br>scipy==1.1.0<br>numpy==1.15.4</strong><br>"
  media:
    image: "/uploads/2019/08/05/resources.png"
    alt_text: uBuild Blocks Mock-Up
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: Getting<strong> Started</strong>
  content: If you have git you can<br><br><strong>$ git clone </strong><a href="https://github.com/usnish/MCC_cluster_tool.git"
    title="https://github.com/usnish/MCC_cluster_tool.git"><strong>https://github.com/usnish/MCC_cluster_tool.git</strong></a>
  media:
    image: "/uploads/2019/08/05/packet.png"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>USAGE </strong>/ FAQ"
  content: '<strong>Introduction to This Tool<br></strong>Rates of multimorbidity
    are rising globally. In the US, patients with multiple chronic conditions account
    for an estimated 70% of all healthcare spending. In recent years, health systems
    have responded to this increasing burden with financial (value-based financing,
    care quality benchmarks) and clinical innovations (care coordination programs,
    co-located specialty clinics). This tool was designed to help analysts and researchers
    determine which segments of their populations who have multiple chronic conditions.
    In addition, it can help sort health systems data by prevalence and attributed
    spending of multiple chronic conditions. The key functionality of this tool lies
    in defining, navigating, and sorting <strong>‘segments’ </strong>within a population.
    Here we define ‘Segments’ as a group of patients defined by 1 or 2 chronic conditions,
    an age group, and legal sex (‘M’ or ‘F’, as represented in insurance claims data).
    These fields should all be available as part of most existing insurance claim
    data sets.<br><br><strong>Generating Chronic Disease Categories<br></strong>We
    have built this tool to be readily compatible with the ICD-9 diagnosis code: chronic
    disease category mapping available from the <a href="https://www.hcup-us.ahrq.gov/toolssoftware/chronic/chronic.jsp"><span
    style="text-decoration: underline;">Healthcare Cost and Utilization Project</span></a>.<br><br><strong>Generating
    Segments:What format does my healthcare data need to be in?</strong>In order to
    utilize this tool, you need to aggregate claims data by member-year. This means
    that each row in your data should represent a single member in a single year of
    utilization.<br><br><strong>How should I go about generating segments?<br></strong>Utilize
    SampleSegmentation.ipynb with your existing data to generate a sample set of segments
    and visualizations. Leave an issue on the github page or contact me at usnishm
    at (g)mail dot com if you have any additional questions.<br><br><strong>Citation:<br></strong><em>Manuscript
    in Press.</em> <br>BMJ Open'
  media:
    image: "/uploads/2019/08/05/questions-1.png"
    alt_text: FAQ
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: License
  content: '<strong>This code is available for free use under the terms of the </strong><a
    href="https://www.gnu.org/licenses/lgpl-3.0.en.html"><strong><span style="text-decoration:
    underline;">GNU LGPLv3.</span></strong></a><span style="text-decoration: underline;"><br></span>Per
    Github: Permissions of this copyleft license are conditioned on making available
    complete source code of licensed works and modifications under the same license
    or the GNU GPLv3. Copyright and license notices must be preserved. Contributors
    provide an express grant of patent rights. However, a larger work using the licensed
    work through interfaces provided by the licensed work may be distributed under
    different terms and without source code for the larger work.<br><br><strong>Read
    the full text of the MCCTool license </strong><a href="https://github.com/usnish/MCC_cluster_tool/blob/master/LICENSE"><strong><span
    style="text-decoration: underline;">here</span></strong></a><strong>.</strong>'
  media:
    image: "/uploads/2019/08/05/copyleft.png"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Troubleshooting</strong>"
  content: 'If you are having problems or have found a bug in the code, please raise
    an issue on the Github page here: <a href="https://github.com/usnish/MCC_cluster_tool/issues"
    title="https://github.com/usnish/MCC_cluster_tool/issues"><span style="text-decoration:
    underline;">https://github.com/usnish/MCC_cluster_tool/issues</span></a>'
  media:
    image: "/uploads/2019/08/05/troubleshooting-1.png"
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