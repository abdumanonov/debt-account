<template>
    <table>
        <thead> СПИСОК ДЕЙТСВУЮЩИХ ДОЛЖНИКОВ
            <tr>
                <th>№</th>
                <th>ПИФНЛ</th>
                <th>ФИО</th>
                <th>Сумма задолженности</th>
                <th>Сумма погашения</th>
                <th>Сумма остатка</th>
                <th>№ договора</th>
                <th>Продукт</th>
                <th>Статус</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>1</th>
                <th>54546453187654</th>
                <th>ALISHEROV ALISGER ALISHEROVICH</th>
                <th>100 000 </th>
                <th>50 000</th>
                <th>50 000</th>
                <th>Solfi 524</th>
                <th>Solfi</th>
                <th>Претензия</th>
            </tr>
        </tbody>
    </table>
</template>
<script>
export default{}
</script>
<style scoped>
table  {
    width: 100%;
    height: 100vh;
    
    background-color: red;

}

table thead {
    border: 1;
    width: 100vw;

    font-weight: bold;
}

table tbody {
    
    display: block;
    width: 100vw;

    
}

table tbody th {

}
</style>