## Kingdee EAS

### 前言

金蝶EAS是一个用Java开发的超大型ERP软件，我维护的版本数据库是SQLServer。

### 契约

> 一个好的系统必须有预先规定的契约，这样流程才能“按规矩”标准化。EAS就是这样一个强契约的系统，这可能因为是从财务软件起家开发的原因吧。

一、 业务链模式
  1. 业务链是指所有业务单据为链式生成。其表现形式为，如果打算删除处于链中某一张业务单据，则失败，必须从链的最末一张单据删除。
