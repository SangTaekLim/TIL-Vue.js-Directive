# Vue.js-Directive

## v-if

뷰 데이터 값의 참거짓   

```
<p v-if="flag">참 인가 거짓인가</p>
```
```
data:{
    flag: true
}
```

##v-for

지정한 데이터 반복 출력

```
<ul>
    <li v-for="ary in ary">{{ ary }}</li>
</ul>
```
```
data:{
     ary: ['1번' , '2번', '3번']
}
```

##v-bind

태그의 기본 속성과 뷰데이터 속성 연결
data- 값도 변경 가능

```
<p v-bind:id="id1">{{ id1 }}</p>
<p v-bind:class="class1">{{ class1 }}</p>
<p v-bind:name="name1">{{ name1 }}</p>
<p v-bind:data-page="data1">{{ data1 }}</p>
```
```
data:{
    id1 : 'id_test',
    class1 : 'class_test',
    name1 : 'name_test',
    data1 : '11111'
},
```
