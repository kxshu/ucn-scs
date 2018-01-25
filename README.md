# 询盘

### 平台功能

主要为记录功能，需记录下采购方和供应商的询盘信息

### 询盘沟通方式

通过固定的表单模式你来我往进行沟通，询盘表为唯一，沟通过程体现为双方你来我往的修改，沟通的表单可添加附件，可勾选单证（单证由采购方提出，供应方满足，遇到平台未提供的单证选项，采购方可在“其他”选项中进行备注说明）

1. 所有字段可编辑
2. 当次变更字段高亮显示
3. 提交后未确认时，不可再被编辑

### 服务商服务

从EXW —&gt; FOB的价格，需要提供价格计算方式。

**待处理问题**：

由谁来选择服务商。

### 客户选择服务商时要实现的目标

1. 客户能看到FOB价格和EXW价格
2. EXW价格转为FOB价格后，是统一的。
3. EXW价格转为FOB价格，公式与系数是固定的。
4. 如果各成本的计算系数可选，则一定由客户发起（这条有争议，需要确认）
5. 可变性/精度的取舍（这条有争议，需要确认）
6. 如果成本系数固定，服务商如何统一（这条有争议，需要确认）

### 应用场景

1. 客户清楚要什么，找谁要  
   完全对应，直接查找（现阶段先实现这一个，其他场景迭代后满足）

2. 客户清楚要什么，不知道找谁要  
   平台推荐+对比功能

3. 客户不清楚要什么，不知道找谁要  
   文字描述，平台介入并推荐+对比功能

4. 供应商主动推送商品信息  
   互相设置白名单或黑名单

5. 数据库未录入的商品  
   客户提出需求，经供应商确认后由供应商录入数据库，最终以QC为准，并单独保留客户的产品库。

### 供应商分类

1. 通过产品分类  
   一级22类

2. 通过交易数据  
   SKU数量、区域

3. 通过数据评估交货时间  
   QC数据（AQL标准），完成率（如±5天acceptable）



