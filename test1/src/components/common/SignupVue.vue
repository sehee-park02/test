<template>
	<div class="container">
        <h1>회원가입</h1>
		<form @submit.prevent="submitForm" class="signUp">
			<div class="signupForm">
                <label for="name">이름 </label>
				<input type="text" id="name" v-model="name" />
			</div>
            <div class="signupForm">
				<label for="id">아이디 </label>
				<input type="text" id="id" v-model="id" />
			</div>
			<div class="signupForm">
                <label for="password">비밀번호 </label>
				<input type="password" id="password" v-model="password" />
			</div>
			<div class="signupForm">
                <label for="passwordConfirm">비밀번호 확인 </label>
				<input type="password" id="passwordConfirm" v-model="passwordConfirm" />
			</div>
            <div class="signupForm">
                <label for="email">이메일 </label>
                <input type="email" id="email" v-model="email" />
            </div>
			<div class="signupForm">
				<label for="position">학과 </label>
				<input type="text" id="magor" v-model="school" />
			</div>
			<div class="signupForm">
				<label for="teamName">전화번호 </label>
				<input type="text" id="phone" v-model="major" />
			</div>
			<input type="submit" class="submit" value="회원가입"/>
		</form>
	</div>
</template>

<script>
export default {
	name: 'SignupForm',
	data() {
		return {
            name: '',
            id: '',
			password: '',
			passwordConfirm: '',
			email: '',
			school: '',
			major: '',
		};
	},
	methods: {
		submitForm() {
			console.log('dd');
		},
	},
};
</script>

<style scoped>
.signUp {
    width: 680px;
    height: 500px;
    border: 1px solid black;
    border-radius: 5px;
    text-align: center;
    margin: auto;
    padding-top: 30px;
}
h1 {
    padding: 30px 0;
    font-size: 50px;
}
.signupForm {
    padding-bottom: 30px;
    width: 650px;
    margin: auto;
}
label {
    font-size: 25px;
    font-weight: bold;
    position: relative;
    text-align: center;
}
input {
    width: 400px;
    height: 30px;
    float: right;
    margin-right: 50px;
    font-size: 20px;
    border-radius: 5px;
    border: 1px solid black;
}
input.submit {
    width: 100px;
    height: 40px;
    font-size: 15px;
    background-color: black;
    color: white;
    border-radius: 5px;
    float: none;
}

</style>