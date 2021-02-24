# Project Submission for HUJI Course 71991 - Population Genetics
## Following 'Genetics of Populations', P.W. Hedrick, Chapter 8


In class we briefly discussed the negative consqeunces of inbreeding in regard to lethal mutations and alleles. Self fertilization ('selfing') is essentially the most extreme form of inbreeding.
 Intuitively, it seems that self fertilization cannot increase the mean fitness of a population. However, self fertilization is relatively abundant in plants, especially in crop & model plants. In these species, some part of the population reproduces by self fertilization as opposed to out-crossing. 
 
 How is that the case? Why was self-fertilization not lost during the evolution of these species? 
 Can it help favoring a genotype that otherwise would not be in favor?
 
 In other words - what is the relationship between natural selection and self fertilization? 

## Model
The model can be seen as constructed from two parts. The first part is the effect of self fertilization on genotype frequencies, and the second is the consideration of fitness in the self-fertilization population.

Allele frequencies are not changed by self fertilization, as will be deomnstrated, so they are not being taken into account. 


<u>Genotype Frequencies </u>

Assuming Hardy-Weinberg proportions, the following equations represent the change in genotype frequency in regard to self-fertilization, where <i>S</i> is the proportion of self-fertilization in the population and <i>T</i> is the complementary proportion of out-crossing. 

The alleles and their corresponding frequencies are <i>p</i> & <i>q</i> (<i>p</i> being the dominant allele) and <i>P</i>,<i>Q</i> are their corresponding homozygotes - <i>H</i> being the heterozygote genotype.


$$ P_1 = Tp^2_0 + S(P_0 + \frac{1}{4} H_0) :: (1.a) $$
$$ Q_1 = Tq^2_0 + S(Q_0 + \frac{1}{4} H_0) :: (1.b) $$
$$ H_1 = 2Tp_0 q_0 + \frac{1}{2}S H_0      :: (1.c) $$

$$ p_1 = P_1 + \frac{1}{2} H_1 = (P_0 + \frac{1}{4} H_0) + \frac{1}{4} H_0 = p_0 $$


$$ H_t = (\frac{1}{2})^t H_0 $$

<u>Natural Selection </u>

First, the notation being used for natural selection is relative fitness based, using dominance degree and selection coefficient <i>h</i>,<i>s</i> respectively, where <i>P</i> is the relatively fitter allele.

$$ \overline{w}_{P} = 1    :: (2.a) $$ 
$$ \overline{w}_{H} = 1-hs :: (2.b) $$ 
$$ \overline{w}_{Q} = 1-s  :: (2.c) $$ 

Since self-fertilization is a form of inbreeding, it is possible to use the equations for genotype fitness values under inbreeding. Since the inbreeding parameter, <i>f</i>, represends the proportion of inbreeding in the population, and the self-fertilization parameter, <i>S</i>, represents the proportion of self-fertilization, assuming that self-fertilization exists in the population but it is the only form of inbreeding that exists for that population, then we can represent that assumption as  <i>S = f</i>.

Accordingly, the mean fitness under no self-fertilization and under self-fertilization in degree <i>f</i> are: 

$$ \overline{w} = p^2 w_P + 2pqw_H + q^2 w_Q                :: (3.a)$$ 
$$ \overline{w}_{f} = \overline{w} + fpq(w_P -2 w_H + w_Q ) :: (3.b)$$ 

Combining equation sets 2 & 3, the extent in which inbreeding/selfing will reduce the mean fitness - termed as the inbreeding depression, the difference between them is:

$$ \overline{w} - \overline{w}_{f} = sfpq(1-2h):: (4)  $$ 
