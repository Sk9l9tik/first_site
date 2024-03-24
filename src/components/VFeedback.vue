<script setup>

</script>

<template>
               <section class="feedback">
                <div class="container">
                    <div class="row justify-content-center">
                        <div class="col-xl-6">
                            <div class="feedback__text">
                                <h2>Остались вопросы?</h2>
                                <p>Свяжитесь с нами!</p>
							</div>
						</div>
                        <div class="col-lg-9 col-xl-6">
							<form action="/" method="post" class="form">
								<label class="mb-3">
									<textarea id="textarea" placeholder="Введите ваш запрос" required></textarea>
								</label>
								<div class="form__group">
									<label>
										<input type="text" name="name" value="" placeholder="Ваше имя" required>
									</label>
									<label>
										<input type="tel" name="name" value="" placeholder="+7(___)___-____" pattern="[+,0-9]{11}" maxlength="11" required>
									</label>
									<label>
										<input type="email" name="name" value="" placeholder="Электронная почта"  required>
									</label>
								</div>
                                <button type="submit" class="btn-prymary">Отправить</button>
							</form>
						</div>
					</div>
				</div>
			</section>
</template>

<style scoped>

</style>
