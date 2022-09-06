<script lang="ts">
	import CollapsibleSection from '$lib/CollapsibleSection.svelte';
</script>

<CollapsibleSection title={"Ranged Weapons To Hit"}>
		<table class="w-full">
			<tr class="border-gray-800 border-b">
				<td class="font-bold">BS Of Shooter</td>
				<td>1</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>7</td>
				<td>8</td>
				<td>9</td>
				<td>10</td>
			</tr>
			<tr>
				<td>D6 Roll Needed</td>
				<td>6</td>
				<td>5</td>
				<td>4</td>
				<td>3</td>
				<td>2</td>
				<td>1</td>
				<td>0</td>
				<td>-1</td>
				<td>-2</td>
				<td>-3</td>
			</tr>
		</table>
</CollapsibleSection>

<CollapsibleSection title="Ranged Hit Modifiers">
	<table>
		<tr>
			<td>-1</td>
			<td>Cover</td>
			<td>If any part of the model is obscured by scenery or other models</td>
		</tr>
		<tr>
			<td>-1</td>
			<td>Long Range</td>
			<td>Shooting at more than half of the weapon's max range</td>
		</tr>
		<tr>
			<td>-1</td>
			<td>Moving & Shooting</td>
			<td>If model has moved at all, other than standing up or turning to face a target</td>
		</tr>
		<tr>
			<td>+1</td>
			<td>Large Target</td>
			<td>If the target is labelled as Large, or whose main body is over 2" tall or wide</td>
		</tr>
	</table>
</CollapsibleSection>

<CollapsibleSection title="Close Combat To Hit">
	<div class="flex items-center">
		<p>Attacker's Weapon Skill</p>
		<table class="table-auto w-full">
			<caption>Defender's Weapon Skill</caption>
			<tr>
				<td>X</td>
				<td>1</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>7</td>
				<td>8</td>
				<td>9</td>
				<td>10</td>
			</tr>
			<tr class="bg-gray-200">
				<td>1</td>
				<td>4</td>
				<td>4</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
			</tr>
			<tr>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
			</tr>
			<tr class="bg-gray-200">
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
				<td>5</td>
			</tr>
			<tr>
				<td>4</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>5</td>
				<td>5</td>
			</tr>
			<tr class="bg-gray-200">
				<td>5</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
			</tr>
			<tr>
				<td>6</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
			</tr>
			<tr class="bg-gray-200">
				<td>7</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
			</tr>
			<tr>
				<td>8</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
				<td>4</td>
			</tr>
			<tr class="bg-gray-200">
				<td>9</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
				<td>4</td>
			</tr>
			<tr>
				<td>10</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>3</td>
				<td>4</td>
			</tr>
		</table>
	</div>
</CollapsibleSection>

<CollapsibleSection title="Wound Chart">
	<div class="flex items-center">
		<p>Weapon or Attacker's Strength</p>
		<table class="table-auto w-full">
			<caption>Target's Toughness</caption>
			<tr>
				<td>X</td>
				<td>1</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>7</td>
				<td>8</td>
				<td>9</td>
				<td>10</td>
			</tr>
			<tr class="bg-gray-200">
				<td>1</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>6</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
			</tr>
			<tr>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>6</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
			</tr>
			<tr class="bg-gray-200">
				<td>3</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>6</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
			</tr>
			<tr>
				<td>4</td>
				<td>2</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>6</td>
				<td>-</td>
				<td>-</td>
				<td>-</td>
			</tr>
			<tr class="bg-gray-200">
				<td>5</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>6</td>
				<td>-</td>
				<td>-</td>
			</tr>
			<tr>
				<td>6</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>6</td>
				<td>-</td>
			</tr>
			<tr class="bg-gray-200">
				<td>7</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
				<td>6</td>
			</tr>
			<tr>
				<td>8</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
				<td>6</td>
			</tr>
			<tr class="bg-gray-200">
				<td>9</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
				<td>5</td>
			</tr>
			<tr>
				<td>10</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>2</td>
				<td>3</td>
				<td>4</td>
			</tr>
		</table>
	</div>
</CollapsibleSection>

<style>
	p {
		writing-mode: vertical-lr;
	}
</style>
