# Title: The Node.js Dependency Ecosystem in GitHub:Social, Technical, and Documentation Aspects


### Abstract: 
Acquired   by   the   largest   social   coding   platform GitHub in 2020, the Node.js Package Manager (i.e., npm) archive repository serves as a critical part of the JavaScript community,and helps support one of the largest developer ecosystems in theworld. Like other software artifacts, the ecosystem now contains rich  information  that  covers  many  different  aspects  of  software development.  To  enable  the  research  community  to  mine  and analyze the diverse data related to Node.js, we built the Node.js dependency  ecosystem  (i.e.,  GH-Node.js),  an  open  dataset  that contains  a  curated  snapshot  of  npm  packages  and  their  clients.Moreover,  we  have  included  related  data  dumps  from  GitHub and the npmJS registry. In addition, GH-Node.js provides accessto issues, pull requests and related vulnerability data. The datasetcan be explored from various aspects, including: (i) Social, sinceit includes all developer information related to the packages and their clients, (ii)Technical, since it includes source code and maintenance  activities  such  as  issues,  pull  requests  and  vulnerability information, and (iii) Documentation, since it features READMEfiles,  code  of  conduct,  and  licensing  information.  Our  vision  is that researchers will use GH-Node.js to investigate their questions with  a  validated  snapshot  of  npm  packages  and  their  clients

## Dataset structure

```
📁 /
├─ 📁 repositories 
├─ 📁 repositories_info
├─ 📁 dependencies_history
├─ 📁 issues
├─ 📁 pull_requests
├─ 📁 contributors
└─ 📁 security_advisories
```


### Authors:
  1. [Bodin Chinthanet∗](https://bchinthanet.com/)
  2. [Syful Islam∗](https://syful-is.github.io/)
  3. [Raula Gaikovina Kula∗](https://naist-se.github.io/contents.html#members)
  4. [Christoph Treude†](http://ctreude.ca/)
  5. [Takashi Ishio∗](https://takashi-ishio.github.io/)
  6. [Hideaki Hata∗](https://hideakihata.github.io/)
  7. [Kenichi Matsumoto*](http://isw3.naist.jp/Contents/Research/cs-05-en.html)
