<template>
  <div>
    <h2>Vue登录界面</h2>
    <form action="/auth/authentication/form" method="post">
      <table>
          <tr>
              <td>用户名：</td>
              <td><input type="text" name="username" value="admin"></td>
          </tr>
          <tr>
              <td>密码：</td>
              <td><input type="password" name="password" value="123456"></td>
          </tr>
          <tr>
              <td colspan="2">
                  <button type="submit">登录</button>
              </td>
          </tr>
      </table>
    </form>
  </div>
</template>
