# awesome-biomedical-data-science-training
List of resources for openly available, ideally freely available, data science training opportunities with a focus on biomedical applications. Contributions welcome...  

Inspired by [awesome-single-cell](https://github.com/seandavi/awesome-single-cell/blob/master/README.md), [awesome-microbes](https://github.com/stevetsa/awesome-microbes)...

[Andre Reindero Bioinformatics Jupyter Notebooks](https://gist.github.com/afrendeiro/8fa43f074a64590c67c30ec7b3141cb7) - A list of jupyter notebooks in bioinformatics

[Awesome-single-cell Tutorials and Workflows](https://github.com/seandavi/awesome-single-cell#tutorials-and-workflows) - Tutorials for single-cell analysis.

[Birmingham Insititute](https://www.bioinformatics.babraham.ac.uk/training.html) - Bioinformatics course, R, Python, Perl, etc.

[Data Carpentry](https://datacarpentry.org/) - Data Carpentry develops and teaches workshops on the fundamental data skills needed to conduct research. Our mission is to provide researchers high-quality, domain-specific training covering the full lifecycle of data-driven research.  

[Data Science Central](https://www.datasciencecentral.com/) - Data Science Central is one of the leading repositories of Data Science content that is regularly updated with the latest trends across domains such as Artificial Intelligence, Machine Learning, Deep Learning, Analytics, Big Data, and much more.  

[Harvard University](https://online-learning.harvard.edu/subject/data-science) - Free online courses in R, visualization, data anlaysis, data wrangling, statistics, AI/ML.  

[Jeff Leek](https://github.com/jtleek) - Data science trianing in [R](https://github.com/jtleek/rpackages), [data sharing](https://github.com/jtleek/datasharing), [data analysis](https://github.com/jtleek/dataanalysis), [genomics paper](https://github.com/jtleek/genomicspapers). 

[National Institute of Health - Office of Data Science Strategy](https://datascience.nih.gov/news) - Find the latest news, announcements, and events related to data science at NIH here.  [Data Science Training at NIH](https://datascience.nih.gov/data-science-training-resources).  

[National Institutes of Health Library](https://www.nihlibrary.nih.gov/services/bioinformatics-support/online-bioinformatics-tutorials) - Training for a range of commercial bioinformatics resources and applications.

[Towards Data Science](https://towardsdatascience.com/) - Towards Data Science is a Medium publication brewing with audience-oriented content not just about Data Science, but a multitude of related technologies such as Machine Learning, Programming, Visualization, and Artificial Intelligence, spanning across more than 5800 published articles.  

# Best Practices


Noble, W. S. (2009). A quick guide to organizing computational biology projects. PLoS Computational Biology, 5(7), e1000424. http://doi.org/10.1371/journal.pcbi.1000424

[NIH Best Practices for Sharing Research Software](https://github.com/seandavi/awesome-single-cell#tutorials-and-workflows) - Best practices for sharing research software and source code, developed under research grants in any stage of development, in a free and open format.

[Ten great papers for biologists starting out in computational biology](https://widdowquinn.github.io/ten_great_papers/)

 - [Noble, W. S. (2009). A quick guide to organizing computational biology projects. PLoS Computational Biology, 5(7), e1000424.](http://doi.org/10.1371/journal.pcbi.1000424)


[Sandve, G. K., Nekrutenko, A., Taylor, J., & Hovig, E. (2013). Ten simple rules for reproducible computational research. PLoS Computational Biology, 9(10), e1003285.](http://doi.org/10.1371/journal.pcbi.1003285)

[Hart, E. M., Barmby, P., LeBauer, D., Michonneau, F., Mount, S., Mulrooney, P., et al. (2016). Ten Simple Rules for Digital Data Storage. PLoS Computational Biology, 12(10), e1005097.](http://doi.org/10.1371/journal.pcbi.1005097)

Your data is everything with a computational project. If it disappears, then your project does, too (so make sure you have multiple backups on multiple sites). The technicalities of ensuring data integrity in the short and long term aren’t often emphasised on undergraduate (or postgraduate) courses, but in the ever more computational world of biology, developing these skills might one day rescue hundreds of thousands of pounds worth of sunk costs. And a career or two. In the meantime, even for small projects, they will give you peace of mind.

Schnell, S. (2015). Ten Simple Rules for a Computational Biologist’s Laboratory Notebook. PLoS Computational Biology, 11(9), e1004385. http://doi.org/10.1371/journal.pcbi.1004385

In addition to storing the data, analyses (and maybe code) you produce - a laboratory notebook recording thoughts and processes is essential. Sometimes it’s also required legally. This is another good paper to read alongside Noble and Sandve et al., as it complements the more technical approaches outlined in those papers.

Kass, R. E., Caffo, B. S., Davidian, M., Meng, X.-L., Yu, B., & Reid, N. (2016). Ten Simple Rules for Effective Statistical Practice. PLoS Computational Biology, 12(6), e1004961. http://doi.org/10.1371/journal.pcbi.1004961

Computational biology often means that there’s an awful lot of data, which means that there’s also often a similarly large amount of accompanying statistical work. This paper describes some general approaches to data management and processing (see also Hart et al.) that will help make your analyses run more smoothly.

Carey, M. A., Papin, J. A. (2018) Ten simple rules for biologists learning to program. PLOS Computational Biology 14(1): e1005871. https://doi.org/10.1371/journal.pcbi.1005871

You are likely, in nearly all computational biology projects, to need to program, and maybe even learn to program. This paper gives excellent practical advice on learning how to program. It covers general strategies for programming, pros and cons of programming languages, and leads into the Wilson et al. and other papers below in a sensible way.

Wilson, G., Aruliah, D. A., Brown, C. T., Chue Hong, N. P., Davis, M., Guy, R. T., et al. (2014). Best Practices for Scientific Computing,PLoS Biology 12(1), e1001745–2. http://doi.org/10.1371/journal.pbio.1001745

If you reach a stage where you are writing your own software (this can happen quite early on any project!) you will benefit from keeping in mind general best practices of software engineering. These play a similar role to aseptic technique in a microbiology lab. They will help you keep your code “uncontaminated” and “clean,” and save you from unnecessary extra work fixing problems, later. There’s no substitute for training, but while you’re waiting for that oversubscribed Carpentries course to have a space (they’re worth waiting for, by the way!), there’s this to read.

Blischak, J. D., Davenport, E. R., & Wilson, G. (2016). A Quick Introduction to Version Control with Git and GitHub. PLoS Computational Biology, 12(1), e1004668. http://doi.org/10.1371/journal.pcbi.1004668

The Wilson et al. paper describes a broad set of software engineering principles, but one principle in particular benefits from the extra detail of this article. Version control will help enable you to keep any code or scripts you write, and any other computational data or activity backed up, reproducible and well-organised. It’s a quite technical topic, especially coming from biology, but once understood it will pay you back many times over.

Perez-Riverol, Y., Gatto, L., Wang, R., Sachsenberg, T., Uszkoreit, J, et al. (2016) Ten Simple Rules for Taking Advantage of Git and GitHub. PLOS Computational Biology 12(7): e1004947. https://doi.org/10.1371/journal.pcbi.1004947

This paper covers some of the same ground as the Blischak paper above, regarding git, but it’s such a central tool for managing and sharing scripts, analyses, and research software that it’s worth emphasising again. This paper takes some of the deliberately technical aspects of the Blischak et al. paper, and extends them to broader applications, like project management, and encouraging collegiality and community-building via GitHub.

Weinberger, C. J., Evans, J. A., & Allesina, S. (2015). Ten simple (empirical) rules for writing science. PLoS Computational Biology, 11(4), e1004205. http://doi.org/10.1371/journal.pcbi.1004205

At some point, you’ll want to describe your work to others. Writing about computational biology is writing about biology. It might be tempting, with a new field, to go into more detail to demonstrate your own understanding, or just because it seems a bit unfamiliar or potentially complex/jargon-ridden to your peers who haven’t made the same journey. But the general principles of scientific writing still apply, and this paper does an excellent (and concise) job of encouraging and demonstrating good scientific writing.


