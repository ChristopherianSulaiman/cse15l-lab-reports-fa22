**Week5-lab-report Christopherian Austin Sulaiman**

The command below shows the command find -name which searches the technical directory for any file/subdirectory which matches the quotations. This is useful if you want to see if a file or directory is in the current directory. When working with a decent sized file, we do not want to be manually searching if a file is in a certain directory. This command would be perfectly suited. This command ONLY prints out the path of the exact file or directory and nothing else.

```
[cs15lfa22fo@ieng6-201]:docsearch:283$ find technical -name "rr74.txt"
technical/biomed/rr74.txt
[cs15lfa22fo@ieng6-201]:docsearch:284$ find technical -name "plos"
technical/plos
[cs15lfa22fo@ieng6-201]:docsearch:285$ find technical -name "biomed"
technical/biomed
[cs15lfa22fo@ieng6-201]:docsearch:286$
```

The command below shows the command find -type d, which searches the technical directory for directories matching the quotes. This command can save time from redundantly searching for directories manually within a directory. This command doesn't only print out the sub directory, but also the directories within the sub directory.

```
[cs15lfa22fo@ieng6-201]:technical:291$ find "government" -type d
government
government/About_LSC
government/Alcohol_Problems
government/Env_Prot_Agen
government/Gen_Account_Office
government/Media
government/Post_Rate_Comm
[cs15lfa22fo@ieng6-201]:technical:292$ find "plos" -type d
plos
[cs15lfa22fo@ieng6-201]:technical:293$ find "biomed" -type d
biomed
```

This command prints out every single file contained in the directory matching the name inside the double quotes. Every path of every single file inside the directory is printed out. I didn't show the full results for each because it was too long.

```
[cs15lfa22fo@ieng6-201]:technical:294$ find "biomed" -type f
biomed/1468-6708-3-1.txt
biomed/1468-6708-3-10.txt
biomed/1468-6708-3-3.txt
biomed/1468-6708-3-4.txt
biomed/1468-6708-3-7.txt
biomed/1471-2091-2-10.txt
biomed/1471-2091-2-11.txt
biomed/1471-2091-2-12.txt
biomed/1471-2091-2-13.txt
biomed/1471-2091-2-16.txt
biomed/1471-2091-2-5.txt
biomed/1471-2091-2-7.txt
biomed/1471-2091-2-9.txt
biomed/1471-2091-3-13.txt
biomed/1471-2091-3-14.txt
biomed/1471-2091-3-15.txt
biomed/1471-2091-3-16.txt
[cs15lfa22fo@ieng6-201]:technical:295$ find "plos" -type f
plos/journal.pbio.0020001.txt
plos/journal.pbio.0020010.txt
plos/journal.pbio.0020012.txt
plos/journal.pbio.0020013.txt
plos/journal.pbio.0020019.txt
plos/journal.pbio.0020028.txt
plos/journal.pbio.0020035.txt
plos/journal.pbio.0020040.txt
plos/journal.pbio.0020042.txt
plos/journal.pbio.0020043.txt
plos/journal.pbio.0020046.txt
plos/journal.pbio.0020047.txt
plos/journal.pbio.0020052.txt
plos/journal.pbio.0020053.txt
plos/journal.pbio.0020054.txt
plos/journal.pbio.0020063.txt
plos/journal.pbio.0020064.txt
plos/journal.pbio.0020067.txt
plos/journal.pbio.0020068.txt
plos/journal.pbio.0020071.txt
plos/journal.pbio.0020073.txt
plos/journal.pbio.0020100.txt
plos/journal.pbio.0020101.txt
plos/journal.pbio.0020105.txt
plos/journal.pbio.0020112.txt
plos/journal.pbio.0020113.txt
plos/journal.pbio.0020116.txt
plos/journal.pbio.0020121.txt
plos/journal.pbio.0020125.txt
plos/journal.pbio.0020127.txt
plos/journal.pbio.0020133.txt
plos/journal.pbio.0020140.txt
plos/journal.pbio.0020145.txt
plos/journal.pbio.0020146.txt
plos/journal.pbio.0020147.txt
plos/journal.pbio.0020148.txt
plos/journal.pbio.0020150.txt
plos/journal.pbio.0020156.txt
[cs15lfa22fo@ieng6-201]:technical:297$ find "government" -type f
government/About_LSC/CONFIG_STANDARDS.txt
government/About_LSC/Comments_on_semiannual.txt
government/About_LSC/LegalServCorp_v_VelazquezDissent.txt
government/About_LSC/LegalServCorp_v_VelazquezOpinion.txt
government/About_LSC/LegalServCorp_v_VelazquezSyllabus.txt
government/About_LSC/ODonnell_et_al_v_LSCdecision.txt
government/About_LSC/ONTARIO_LEGAL_AID_SERIES.txt
government/About_LSC/Progress_report.txt
government/About_LSC/Protocol_Regarding_Access.txt
government/About_LSC/Special_report_to_congress.txt
government/About_LSC/State_Planning_Report.txt
government/About_LSC/State_Planning_Special_Report.txt
government/About_LSC/Strategic_report.txt
government/About_LSC/commission_report.txt
government/About_LSC/conference_highlights.txt
government/About_LSC/diversity_priorities.txt
government/About_LSC/reporting_system.txt
government/Alcohol_Problems/DraftRecom-PDF.txt
government/Alcohol_Problems/Session2-PDF.txt
government/Alcohol_Problems/Session3-PDF.txt
government/Alcohol_Problems/Session4-PDF.txt
government/Env_Prot_Agen/1-3_meth_901.txt
government/Env_Prot_Agen/atx1-6.txt
government/Env_Prot_Agen/bill.txt
government/Env_Prot_Agen/ctf1-6.txt
government/Env_Prot_Agen/ctf7-10.txt
government/Env_Prot_Agen/ctm4-10.txt
government/Env_Prot_Agen/final.txt
government/Env_Prot_Agen/jeffordslieberm.txt
government/Env_Prot_Agen/multi102902.txt
government/Env_Prot_Agen/nov1.txt
government/Env_Prot_Agen/ro_clear_skies_book.txt
government/Env_Prot_Agen/section-by-section_summary.txt
government/Env_Prot_Agen/tech_adden.txt
government/Env_Prot_Agen/tech_sectiong.txt
government/Gen_Account_Office/GovernmentAuditingStandards_yb2002ed.txt
government/Gen_Account_Office/InternalControl_ai00021p.txt
government/Gen_Account_Office/July11-2001_gg00172r.txt
government/Gen_Account_Office/June30-2000_gg00135r.txt
government/Gen_Account_Office/Letter_WalkerJan30-2001.txt
government/Gen_Account_Office/Letter_Walkeraug17let.txt
government/Gen_Account_Office/May1998_ai98068.txt
government/Gen_Account_Office/Oct15-1999_gg00026t.txt
government/Gen_Account_Office/Oct15-2001_d0224.txt
government/Gen_Account_Office/Paper_Walker11-2002_acpro122.txt
government/Gen_Account_Office/Sept14-2002_d011070.txt
government/Gen_Account_Office/Sept27-2002_d02966.txt
government/Gen_Account_Office/Statements_Feb28-1997_volume.txt
government/Gen_Account_Office/Testimony_Jul15-2002_d02940t.txt
government/Gen_Account_Office/Testimony_Jul17-2002_d02957t.txt
government/Gen_Account_Office/Testimony_cg00010t.txt
government/Gen_Account_Office/Testimony_d01609t.txt
government/Gen_Account_Office/ai00134.txt
government/Gen_Account_Office/ai2132.txt
government/Gen_Account_Office/ai9868.txt
government/Gen_Account_Office/d01121g.txt
government/Gen_Account_Office/d01145g.txt
government/Gen_Account_Office/d01186g.txt
government/Gen_Account_Office/d01376g.txt
```

