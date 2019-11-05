<template>
    <div>
        <div class="page-title">
            <h3>Список товаров</h3>
        </div>

        <section>
            <table>
                <thead>
                    <tr>
                        <th>ID</th>
                        <th>Название</th>
                        <th>Категория</th>
                        <th>Дата поставки</th>
                        <th>Вид</th>
                        <th>Наличие</th>
                    </tr>
                </thead>

                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Acer Aspire F15</td>
                        <td>Компьютер</td>
                        <td>10.09.16</td>
                        <td>
                            <img src="../assets/img/1.jpg" alt="Acer Aspire F15">
                        </td>
                        <td>
                            <span class="white-text badge red">Нет в наличии</span>
                        </td>
                    </tr>
                    <tr>
                        <td>2</td>
                        <td>Iphone 11 Pro Max</td>
                        <td>Телефон</td>
                        <td>10.10.19</td>
                        <td>
                            <img src="../assets/img/2.jpg" alt="Iphone 11 Pro Max">
                        </td>
                        <td>
                            <span class="white-text badge green">Есть в наличии</span>
                        </td>
                    </tr>
                </tbody>
            </table>
        </section>
    </div>
</template>
