<script>
import ExampleForm from './ExampleForm.vue';
import PreviewMultilingual from './previews/PreviewMultilingual.vue';

export default {
	extends: ExampleForm,
	components: {
		PreviewMultilingual
	},
	data() {
		return {
			props: PreviewMultilingual.data().components.example,
			component: 'preview-multilingual'
		};
	}
};
</script>
