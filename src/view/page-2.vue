<!--
 * @Author: lx000
 * @Date: 2021-11-10 11:38:58
 * @LastEditTime: 2021-11-19 09:10:01
 * @Description: 描述
-->

<template>
  <Container>
    <a-page-header
        title="角色交易"
        sub-title="选中的角色将转移给对方账号" />
    <a-divider style="background-color:#b99d6e;"/>
    <div>
      <a-space>
        选择我的角色
        <a-select style="width: 120px">
          <a-select-option value="jack">mysumama</a-select-option>
          <a-select-option value="lucy">dianfa</a-select-option>
          <a-select-option value="Yiminghe">druuuuu</a-select-option>
        </a-select>
      </a-space>
    </div>
    <a-divider style="background-color:#b99d6e"/>
    <div>
      <a-space>
        选择对方账号
        <a-select style="width: 120px">
          <a-select-option value="jack">user1</a-select-option>
          <a-select-option value="lucy">user2</a-select-option>
          <a-select-option value="Yiminghe">user3</a-select-option>
        </a-select>
      </a-space>
    </div>
    <a-divider style="background-color:#b99d6e;"/>
    <div>
      
      <a-space>
        <a-button type="primary">交易</a-button>
      </a-space>
    </div>
  </Container>
</template>
