---
order: 6
title:
  zh-CN: 不可选择日期和时间
  en-US: Disabled Date & Time
---

## zh-CN

可用 `nzDisabledDate` 和 `nzDisabledTime` 分别禁止选择部分日期和时间。

import differenceInCalendarDays from 'date-fns/difference_in_calendar_days';
import setHours from 'date-fns/set_hours';

上面两句改为使用下面的方式(我使用的是：Angular7)：

import { differenceInCalendarDays,setHours } from 'date-fns';

不然后报错：InnerPopupComponent.html:12 ERROR TypeError: difference_in_calendar_days_1.default is not a function；

## en-US

Disabled part of dates and time by `nzDisabledDate` and `nzDisabledTime` respectively.


