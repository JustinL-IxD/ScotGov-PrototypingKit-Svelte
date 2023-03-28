<style>
    .radio-label{
        font-family: "Roboto", sans-serif;
        display: flex;
        align-items: center;
        cursor: pointer;
        position: relative;
    }

    .radio-container {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 48px;
        width: 48px;
        border: 2px solid #333333;
        border-radius: 50%;
        margin-right: 10px;
    }

    .radio-input {
        position: absolute;
        top: 0;
        left: 0;
        height: 100%;
        width: 100%;
        opacity: 0;
        cursor: pointer;
        margin: 0;
    }

    .radio-input:focus + .radio-container {
        outline: 2px solid #fdd522;
    }

    .radio-input:checked + .radio-container::before{
        content: "";
        display: block;
        height: 30px;
        width: 30px;
        background-color: #333333;
        border-radius: 50%;
    }
</style>

<div class="flex flex-col">
    {#each ['option 1', 'option 2', 'option 3'] as value (value)}
        <label class="radio-label mb-2">
            <input type="radio" class="radio-input" name="options" value="{value}" />
            <div class="radio-container"></div>
            {value}
        </label>
    {/each}
</div>