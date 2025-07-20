<script>
    import Scroller from "../lib/Scroller.svelte";
    import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="right">
        {#snippet sticky()}
            <img class="hispanic_edu-img" src="hispanic_edu.png" alt="hispanic Education" />
            <img class="hispanic_emp-img" src="hispanic_emp.png" alt="hispanic Employment" />
        {/snippet}

        {#snippet scrolly()}
             <ArticleText>
                <strong>
                   We will dive into the Hispanic degree attainment rates and the annual earnings.
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                     The graph reveals the average of degree attainment rates each year. It is evident that the highest 
                     average attainment rate happened in 2023 with approximately 48% which indicates a great increase
                     after being below fourties in 2011 and 2012.
                     
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                    The low household income may be the reason for Hispanic having the lowest  
                    average of degree attainment rates among all races. 
                </strong>
            </ArticleText>

            <ArticleText><strong>
                   This graph shows the average of annual median earnings for full-time workers. The highest average of 
                   median earnings occured in 2021 with above 50,500$ which is higher than the earnings of Black
                   despite having lower degree attainment rate than Black.
                
                </strong>
            </ArticleText>

            <ArticleText><strong>
                  Hispanic who have limited English skills may face challenges in 
                  accessing higher-paying employment opportunities.
                </strong>
            </ArticleText>
        {/snippet}
    </Scroller>
</div>

<style>
    .hispanic_edu-img {
         width: 80%;
         margin-top: 15rem;
    }

     .hispanic_emp-img {
        width: 80%;
        margin-top: 3rem;
    }
</style>


