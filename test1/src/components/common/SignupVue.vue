<template>
	<div class="container">
		<form @submit.prevent="submitForm">
			<div>
                <label for="name">이름</label>
				<input type="text" id="name" v-model="name" />
			</div>
            <div>
				<label for="id">아이디</label>
				<input type="text" id="id" v-model="id" />
			</div>
			<div>
                <label for="password">비밀번호</label>
				<input type="password" id="password" v-model="password" />
			</div>
			<div>
                <label for="passwordConfirm">비밀번호 확인</label>
				<input type="password" id="passwordConfirm" v-model="passwordConfirm" />
			</div>
            <div>
                <label for="email">이메일</label>
                <input type="text" id="email" v-model="email" />
            </div>
			<div>
				<label for="position">학교</label>
				<input type="text" id="school" v-model="school" />
			</div>
			<div>
				<label for="teamName">학과</label>
				<input type="text" id="major" v-model="major" />
			</div>
			<button type="submit">회원가입</button>
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

<style scoped></style>