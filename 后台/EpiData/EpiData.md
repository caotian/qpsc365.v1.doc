# EpiData下载

> 更新记录

<table>
    <tr>
        <th style="width:250px;">日期</th>
        <th>更新内容</th>
    </tr>
    <tr>
        <td>2018-06-04 10:53:38</td>
        <td>生成时间</td>
    </tr>
</table>

## EpiData下载

```
GET /admin/epi-data/download
```

> 参数

<table>
    <tr>
        <th style="width:150px;">属性名称</th>
        <th style="width:60px;">类型</th>
        <th style="width:60px;">必填</th>
        <th style="width:200px;">说明</th>
        <th>备注</th>
    </tr>
    <tr>
        <td>plan_id</td>
        <td>int</td>
        <td>-</td>
        <td>筛查计划ID</td>
        <td>不传则默认当前筛查计划ID</td>
    </tr>
    <tr>
        <td>county</td>
        <td>string</td>
        <td>-</td>
        <td>县(区)</td>
        <td>-</td>
    </tr>
    <tr>
        <td>street</td>
        <td>string</td>
        <td>-</td>
        <td>街道</td>
        <td>-</td>
    </tr>
    <tr>
        <td>school_id</td>
        <td>int</td>
        <td>-</td>
        <td>学校ID</td>
        <td>-</td>
    </tr>
</table>