####Name
_Dubovicky Dmitry_
####Contacts for communication
+ dubovizckij.dmitry@gmail.com
+ duboviczkij.dmitrij@mail.ru
####Brief information
I want to become a professional frontend developer so the quality of knowledge is very important for me
####Skills
+ html
+ ccs
+ js
+ c#
+ visual code
+ visual studio
+ git
+ github
####Code Examples

___A fragment of html code:___
```
@model AuctionApp.Entities.Auction

@{
    ViewData["Title"] = "Edit";
}

<h1>Edit</h1>

<h4>Auction</h4>
<hr />
<div class="row">
    <div class="col-md-4">
        <form asp-action="Edit">
            <div asp-validation-summary="ModelOnly" class="text-danger"></div>
            <input type="hidden" asp-for="Id" />
            <div class="form-group">
                <label asp-for="StartDate" class="control-label"></label>
                <input asp-for="StartDate" class="form-control" />
                <span asp-validation-for="StartDate" class="text-danger"></span>
            </div>
            <div class="form-group form-check">
                <label class="form-check-label">
                    <input class="form-check-input" asp-for="Status" /> @Html.DisplayNameFor(model => model.Status)
                </label>
            </div>
            <div class="form-group">
                <label asp-for="UserId" class="control-label"></label>
                <select asp-for="UserId" class="form-control" asp-items="ViewBag.UserId"></select>
                <span asp-validation-for="UserId" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="TransitId" class="control-label"></label>
                <select asp-for="TransitId" class="form-control" asp-items="ViewBag.TransitId"></select>
                <span asp-validation-for="TransitId" class="text-danger"></span>
            </div>
            <div class="form-group">
                <input type="submit" value="Save" class="btn btn-primary" />
            </div>
        </form>
    </div>
</div>

<div>
    <a asp-action="Index">Back to List</a>
</div>

@section Scripts {
    @{await Html.RenderPartialAsync("_ValidationScriptsPartial");}
}

```
####Work experience
Writing laboratory, coursework while studying at the university
####Education
Graduated from the Belarusian-Russian University in Mogilev in 2021. 
####English language
Studied English at university
At the moment I'm learning English using apps and movies