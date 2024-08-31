# MetaIBM (Metacommunity Individual-based Modelling)
## This is the formal released version.2.9.12 
### a python-based library for building a Individual-based model in Community Ecology 
#### metacommunity_IBM.py is the source code of the library (version.2.9.12).
#### MetaIBM users mannual.docx is the user mannual of the library
#### we also provided four examples of how to use to library to built a IBMs by the users
#### Note that other versions of this library providing other advanced algorithms is also avaiable in the brance of the repository.

Table of contents
1.	INTRODUCTION	2
2.	INSTALLATION	3
2.1	WINDOWS PLATFORM	3
2.2	LINUX PLATFORM	4
2.3	MACOS PLATFORM WITH APPLE SILICON	4
2.4	IMPORTING THE METAIBM MODULE IN PYTHON	5
3.PROCESSES AND SUB-MODELS	5
3.1 LANDSCAPE TOPOLOGY OF A METACOMMUNITY	5
3.1.1 Habitat scales	5
3.1.2 patch scales	7
3.1.3 global scales or metacommunity scales	9
3.2 SPECIES AND INDIVIDUALS’ ATTRIBUTES SETTING	11
3.2.1 Individuals and attributes	11
3.2.2 the data structure of metaIBM.individual.genotype_set	14
3.2.3 the data structure of metaIBM.individual.phenotype_set	14
3.3 ENVIRONMENT GRADIENTS AND FITNESS LANDSCAPE	15
3.3.1 Environment gradients	15
3.3.2 fitness landscape	18
3.4 COLONIZATION PROCESS	20
3.4.1 create an islands-mainland modelling system	20
3.4.2 modelling the Colonization process	23
3.5 NATURAL SELECTION OR ENVIRONMENTAL FILTERS PROCESS	25
3.6 REPRODUCTION AND MUTATION PROCESSES	26
3.6.1 asexual reproduction	26
3.6.2 sexual reproduction	27
3.6.3 mutation	28
3.7 DISPERSAL PROCESS	28
3.7.1 the dispersal of propagules	28
3.7.2 Dispersal among patches	28
3.7.3 Dispersal within a patch	30
3.8 DORMANCY PROCESS	31
3.9 DISTURBANCE PROCESS	32
3.9.1 Disturbance in a habitat	32
3.9.2 Disturbance in a patch	32
4.INPUT	33
5.OUTPUT	33
5.1 THE GUI SYSTEM OF THE SOFTWARE	33
5.1.1 showing environmental gradients	34
5.1.2 showing species distribution	35
5.1.3 showing species phenotype in the metacommunity	36
5.2 OTHER FORM OF OUTPUT	37
5.2.1 saving species distribution data into a csv file	38
5.2.2 saving species phenotypes data into a csv file	39
6.EXAMPLES OF SIMULATION	41
7.HIGH PERFORMANCE COMPUTING (HPC)	41
7.1 INSTALLATION OF MPI SOFTWARE AND MPI4PY PYTHON MODULE	42
7.1.1 Windows platform	42
7.1.2 Linux platform	43
7.1.3 MacOS platform with Apple Silicon	43
7.2 EXAMPLES OF PARALLEL-COMPUTING	44
8.REFERENCES	45
9.ACKNOWLEDGEMENTS	46

