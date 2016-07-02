# PrescriptionTrackSystem
##系统要求
处方管理系统的构建是以医师处方为中心，实时录入病人信息，开处方，生成处方，进行数据的统计，简化了传统处方信息处理的过程。本系统的重点是跟踪处方的信息数据并处理数据，处理数据时相关的数据对象有如下有以下：
（1）系统跟踪每位顾客的以下信息：
	顾客姓名、电话号码、出生日期、承保公司、保险号、处方历史记录
（2）每位顾客的服药史将记录下列每次处方信息：
	由药房给出的唯一的处方ID 号、处方开出的药物、开处方的医生姓名和电话号码、处方日期、处方终止日期、有效购药次数、配药“单位”数量（此处的“单位”可能是片、匙和毫升等———见后面关于药品的讨论）、如果有其它替代品，是否可以向顾客提供替代品。
（3）对于药房存货的每种药品，系统应跟踪的如下：
	药品名称，药品“单位”（片、匙和毫升等），哪些其它药品可以作为另一种这种药品的替代品，服用药品可能引起的副作用。
（4）系统所支持的查询功能：
    服药史，即给定顾客的所有处方历史记录—根据顾客的要求提供的报告，某种给定药品的副作用报告，随处方一起提供某种给定药品的可替换药品列表一份给定处方是否还有购药许可：即，是否还可以凭处方购药，以及处方是否已经过期。 