<template>
  <div>
    <div class="page-title">
      <h3>Пользователи</h3>
    </div>

    <div class="row">

      <div class="col s12 m6 l8">
        <div class="card darken-3 bill-card">
          <div class="card-content white-text">
            <div class="card-header">
              <span class="card-title">Список пользователей</span>
            </div>
            <table>
              <thead>
              <tr>
                <th>Имя</th>
                <th>Дата регистрации</th>
                <th>Статус</th>
              </tr>
              </thead>

              <tbody>
              <tr>
                <td>Александров Александр Александрович</td>
                <td>10.05.19</td>
                <td>Администратор</td>
              </tr>
              <tr>
                <td>Сергеев Сергей Сергеевич</td>
                <td>05.06.19</td>
                <td>Модератор</td>
              </tr>
              <tr>
                <td>Михайлов Михаил Михайлович</td>
                <td>08.07.19</td>
                <td>Пользователь</td>
              </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>
