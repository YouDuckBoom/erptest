<template>
  <div>
    <el-col :span="11">
      <label>单号日期</label>
      <el-date-picker type="date" placeholder="选择日期" style="width: 100%;"></el-date-picker>
    </el-col>

    <el-col :span="1">
      <span>&nbsp;</span>
    </el-col>

    <el-col :span="11">
      <label>单据号码</label>
      <el-input></el-input>
    </el-col>

    <el-col :span="11">
      <label>增值科目</label>
      <el-input></el-input>
    </el-col>

    <el-col :span="1">
      <span>&nbsp;</span>
    </el-col>
    
    <el-col :span="11">
      <label>凭据号码</label>
      <el-input></el-input>
    </el-col>

    <el-col :span="11">
      <label>减值科目</label>
      <el-input></el-input>
    </el-col>

    <el-col :span="1">
      <span>&nbsp;</span>
    </el-col>
    
    <el-col :span="11">
      <label>凭据号码</label>
      <el-input></el-input>
    </el-col>

    <el-table
    stripe
    style="width: 100%">
    <el-table-column
      label="编号"
      width="180">
    </el-table-column>
    <el-table-column
      label="物料编号"
      width="180">
    </el-table-column>
    <el-table-column
      label="物料名称">
    </el-table-column>
    <el-table-column
      label="规格型号">
    </el-table-column>
    <el-table-column
      label="单位">
    </el-table-column>
  </el-table>
   
    <el-col :span="11">
      <label>制单人员</label>
      <el-input></el-input>
    </el-col>

     <el-col :span="1">
      <span>&nbsp;</span>
    </el-col>


    <el-col :span="11">
      <label>复核人员</label>
      <el-input></el-input>
    </el-col>

    <el-col :span="24">
      <span>&nbsp;</span>
    </el-col>
    <el-button type="primary">保存</el-button>
      <el-button>重置</el-button>
  </div>
</template>